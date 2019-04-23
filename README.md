# CollectionView Challenge

Following up on the [Visual Challenge](https://github.com/davidortinau/VisualChallenge), the CollectionView Challenge is aimed at taking a previous or current project's ListView and convert it to the new CollectionView.

_Note: Some functionality may not be (fully) implemented yet as of this time. We're working to make sure that it is, but we still want your feedback on what's available now!_

## Challenge Quick Start

1. Fork this repository
2. Open `CollectionViewChallengePage.xaml`
3. Take a ListView from another project, previous or current, and convert it to a CollectionView, replacing the placeholder on the page. If you need to, you can replace any data with placeholders; the goal is to replicate the functionality that your app's ListView utilizes.
4. Submit a pull request of your progress back to this repository. Please include the following feedback:
   - Comparison screenshots of your results! If you really want to go the extra mile, video is awesome to see, too.
   - Your experience converting the `ListView` to a `CollectionView` (Any difficulties?)
   - How is the performance compared to the `ListView`?
   - Is there anything missing that you'd like to see?

`CollectionView` docs can be found [here](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/collectionview/).

## Feedback

1. No `SwipeView`, I was really hoping to see this at launch.
2. In the sample, the first few items in the list were hidden behind the navigation title.
3. Nothing shows in Android using the following markup:

```xml
<CollectionView>
                <CollectionView.ItemsSource>
                    <x:Array Type="{x:Type x:String}">
                        <x:String>Hello, Twitch!</x:String>
                        <x:String>This is a CollectionView!</x:String>
                        <x:String>Your feedback on the experience of converting a ListView to a CollectionView is incredibly appreciated.</x:String>
                        <x:String>Here are three general questions:</x:String>
                        <x:String>1. How was the experience of converting your existing ListView to a CollectionView?</x:String>
                        <x:String>2. How is the performance compared to the ListView?</x:String>
                        <x:String>3. Is there a specific piece of functionality that you'd like to see?</x:String>
                        <x:String>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Scelerisque varius morbi enim nunc faucibus a pellentesque. Penatibus et magnis dis parturient montes nascetur. Morbi blandit cursus risus at ultrices mi tempus imperdiet. In hendrerit gravida rutrum quisque non. Mollis nunc sed id semper risus in hendrerit. Aliquet lectus proin nibh nisl condimentum id venenatis a condimentum. Quis imperdiet massa tincidunt nunc pulvinar sapien et ligula. Ut aliquam purus sit amet. Molestie a iaculis at erat pellentesque adipiscing commodo. Pretium nibh ipsum consequat nisl vel pretium. Ut lectus arcu bibendum at varius vel pharetra vel. Duis tristique sollicitudin nibh sit amet commodo nulla facilisi. Bibendum neque egestas congue quisque egestas diam. Quisque id diam vel quam elementum pulvinar etiam non quam.</x:String>
                        <x:String>Tellus integer feugiat scelerisque varius morbi enim nunc faucibus a. Volutpat commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Amet porttitor eget dolor morbi non arcu. Nam libero justo laoreet sit amet cursus sit amet. Id aliquet lectus proin nibh nisl condimentum id venenatis. Amet consectetur adipiscing elit ut aliquam purus sit amet. Sed lectus vestibulum mattis ullamcorper velit sed ullamcorper morbi. Tortor dignissim convallis aenean et tortor at risus viverra. Quis viverra nibh cras pulvinar mattis. Sit amet tellus cras adipiscing enim eu turpis. Elementum integer enim neque volutpat ac tincidunt vitae. Tristique risus nec feugiat in fermentum posuere urna nec. Non tellus orci ac auctor. Sit amet cursus sit amet dictum. Purus gravida quis blandit turpis cursus in hac habitasse platea. Rhoncus urna neque viverra justo nec ultrices. Dapibus ultrices in iaculis nunc sed augue lacus viverra vitae.</x:String>
                        <x:String>Nullam eget felis eget nunc lobortis mattis. Integer vitae justo eget magna fermentum iaculis eu non. Erat nam at lectus urna duis convallis convallis tellus id. Fermentum leo vel orci porta. Ullamcorper dignissim cras tincidunt lobortis feugiat vivamus at augue eget. Tellus elementum sagittis vitae et leo duis ut. Nisi scelerisque eu ultrices vitae auctor eu augue ut. Tincidunt lobortis feugiat vivamus at augue eget. Orci porta non pulvinar neque laoreet suspendisse interdum. Leo in vitae turpis massa sed elementum tempus. Mauris sit amet massa vitae tortor condimentum lacinia. Eget arcu dictum varius duis at consectetur lorem donec. Pellentesque dignissim enim sit amet venenatis. At urna condimentum mattis pellentesque id. Etiam non quam lacus suspendisse faucibus interdum posuere. Pellentesque habitant morbi tristique senectus et netus. Urna et pharetra pharetra massa massa.</x:String>
                        <x:String>Ac ut consequat semper viverra nam libero. Semper viverra nam libero justo laoreet sit. Risus sed vulputate odio ut enim blandit volutpat. Pulvinar mattis nunc sed blandit libero volutpat. Augue ut lectus arcu bibendum at varius vel pharetra vel. Adipiscing vitae proin sagittis nisl rhoncus mattis. Egestas tellus rutrum tellus pellentesque eu. Parturient montes nascetur ridiculus mus mauris vitae ultricies leo integer. Lorem ipsum dolor sit amet consectetur adipiscing. Auctor urna nunc id cursus metus.</x:String>
                        <x:String>Elit sed vulputate mi sit amet mauris. Eget arcu dictum varius duis at. Sit amet facilisis magna etiam tempor orci eu lobortis. Hendrerit dolor magna eget est lorem ipsum dolor. Molestie ac feugiat sed lectus vestibulum mattis ullamcorper velit. Mauris ultrices eros in cursus turpis massa tincidunt dui ut. Morbi tristique senectus et netus et. At tempor commodo ullamcorper a. Odio morbi quis commodo odio aenean sed adipiscing diam. In egestas erat imperdiet sed euismod nisi. Sed odio morbi quis commodo odio aenean sed. Velit laoreet id donec ultrices tincidunt arcu non sodales. Purus sit amet luctus venenatis lectus magna. Sed blandit libero volutpat sed. Praesent tristique magna sit amet purus gravida quis blandit. Facilisi morbi tempus iaculis urna id volutpat lacus laoreet non.</x:String>
                        <x:String>Id cursus metus aliquam eleifend mi in. Blandit massa enim nec dui nunc mattis enim ut tellus. Sollicitudin nibh sit amet commodo nulla facilisi nullam vehicula. Urna cursus eget nunc scelerisque viverra. At augue eget arcu dictum. Elit pellentesque habitant morbi tristique senectus. Tempus iaculis urna id volutpat lacus laoreet non curabitur gravida. Molestie ac feugiat sed lectus vestibulum mattis. Consectetur adipiscing elit duis tristique sollicitudin nibh sit. Et netus et malesuada fames ac turpis egestas integer. Aenean vel elit scelerisque mauris. Placerat vestibulum lectus mauris ultrices. Velit aliquet sagittis id consectetur purus ut faucibus pulvinar elementum.</x:String>
                        <x:String>Tempor orci eu lobortis elementum nibh tellus. Lectus quam id leo in vitae. Metus dictum at tempor commodo ullamcorper a lacus vestibulum sed. Pulvinar neque laoreet suspendisse interdum consectetur libero. Orci nulla pellentesque dignissim enim sit amet. Aliquam ut porttitor leo a diam. Ultricies mi quis hendrerit dolor. A diam maecenas sed enim. Nunc sed id semper risus in hendrerit. Sit amet porttitor eget dolor morbi non arcu risus quis. Phasellus faucibus scelerisque eleifend donec pretium vulputate sapien. At quis risus sed vulputate odio ut enim. Odio eu feugiat pretium nibh ipsum. Scelerisque fermentum dui faucibus in ornare. Ut eu sem integer vitae justo eget magna fermentum. Elit duis tristique sollicitudin nibh sit amet. Nunc scelerisque viverra mauris in aliquam sem fringilla ut.</x:String>
                        <x:String>Tincidunt nunc pulvinar sapien et ligula. Habitasse platea dictumst vestibulum rhoncus est pellentesque elit. Mauris augue neque gravida in fermentum et sollicitudin ac orci. Felis eget nunc lobortis mattis aliquam faucibus purus in massa. Iaculis urna id volutpat lacus. A iaculis at erat pellentesque adipiscing commodo. Posuere ac ut consequat semper viverra nam libero. Ornare arcu odio ut sem nulla pharetra diam. Quisque id diam vel quam. Imperdiet dui accumsan sit amet. Dolor purus non enim praesent elementum facilisis leo. Purus in mollis nunc sed id semper. Blandit massa enim nec dui nunc mattis. Dapibus ultrices in iaculis nunc sed augue lacus viverra. Sit amet mattis vulputate enim nulla aliquet porttitor lacus luctus. Aliquam vestibulum morbi blandit cursus risus at ultrices mi tempus.</x:String>
                        <x:String>Amet nisl suscipit adipiscing bibendum est ultricies integer. Eu scelerisque felis imperdiet proin fermentum leo vel. Cursus eget nunc scelerisque viverra mauris in aliquam sem. Eleifend mi in nulla posuere sollicitudin aliquam ultrices sagittis. Velit laoreet id donec ultrices tincidunt arcu. Dui nunc mattis enim ut. Posuere sollicitudin aliquam ultrices sagittis orci a scelerisque purus. Dictum non consectetur a erat nam at lectus urna. Quis imperdiet massa tincidunt nunc pulvinar. Varius duis at consectetur lorem. Pretium vulputate sapien nec sagittis aliquam malesuada bibendum. Enim neque volutpat ac tincidunt vitae semper quis lectus nulla. Sagittis orci a scelerisque purus semper eget duis at tellus.</x:String>
                        <x:String>Est ultricies integer quis auctor. Fermentum odio eu feugiat pretium nibh ipsum. Aenean vel elit scelerisque mauris pellentesque pulvinar pellentesque habitant morbi. Purus viverra accumsan in nisl nisi. Nec dui nunc mattis enim ut tellus elementum sagittis. Quis commodo odio aenean sed. Urna nec tincidunt praesent semper feugiat. Pulvinar etiam non quam lacus suspendisse faucibus interdum posuere lorem. Luctus accumsan tortor posuere ac. Lectus sit amet est placerat in. Eu lobortis elementum nibh tellus molestie nunc non blandit. Dictum sit amet justo donec enim diam vulputate. Suspendisse faucibus interdum posuere lorem ipsum dolor sit amet. Et netus et malesuada fames ac turpis egestas sed tempus.</x:String>
                    </x:Array>
                </CollectionView.ItemsSource>
                <CollectionView.ItemsLayout>
                    <GridItemsLayout Orientation="Vertical" Span="3"/>
                </CollectionView.ItemsLayout>
                <CollectionView.ItemTemplate>
                    <DataTemplate>
                        <Grid Padding="5">
                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="Auto"/>
                                <ColumnDefinition Width="100" />
                            </Grid.ColumnDefinitions>
                            <Grid.RowDefinitions>
                                <RowDefinition Height="Auto" />
                            </Grid.RowDefinitions>
                            <Label Grid.Column="0" Text="*" />
                            <Label Grid.Column="1" Text="{Binding .}" d:Text="Design Time Data" FontSize="10"/>
                        </Grid>
                    </DataTemplate>
                </CollectionView.ItemTemplate>
            </CollectionView>
```