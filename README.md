# StepThroughListView
Customize a horizontal listview with left/right button on uwp
![vivi](https://github.com/hupo376787/StepThroughListView/blob/master/298986-20191111170424534-1670385774.png)

SO link: https://stackoverflow.com/questions/58298747/how-to-customize-a-horizontal-listview-with-left-right-button-on-uwp

cnBlog: https://www.cnblogs.com/hupo376787/p/11837285.html

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





