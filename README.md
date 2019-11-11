# StepThroughListView
Customize a horizontal listview with left/right button on uwp
Usage:


        <ctl:StepThroughListView
              AlwaysShowButton="Collapsed"
              ItemsSource="{x:Bind product}"
              Tapped="StepThroughListView_Tapped">
        </ctl:StepThroughListView>
                    
                    
        private void StepThroughListView_Tapped(object sender, TappedRoutedEventArgs e)
        {
            var item = (sender as Controls.StepThroughListView).SelectedItem as ProductItem;
            if (item != null)
            {
                //TODO...
            }
        }





