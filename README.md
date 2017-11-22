# fashionapp
fashion app is simplay an app that displays the information about four brands
each brand has many attributes name, logo, founder, .....
all values of each brand are found in string.xml
all brands are intialised in BrandListFragment and it has an adapter that displays the logo of the brand
BrandWikiFragment is when the user select a brand form the list
an instance of BrandWikiFragment is created and it holds the brand info in its layout
in addition BrandWikiFragment had the brand website
so when the user click it WebDialogFragment should appear for the user
and also there is a button (View images) when the user click it an view pager is created for that brand
and it displays the four images for the brand

problem: I cannot extract brand website in WebDialogFramnet
and when I do so I get null pointer exception as well as the view pager
I do not know how to diaply the for images probarly because there are for arrays
and all the examples that I saw online are 1 array.

