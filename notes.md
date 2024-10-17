## AA

the long shopify url that comes when you do shopify dev is actually the development branch. 
When you open localhost, it actually reflects the changes you make in that dev branch. That way, you upload your files assets etc. to test on shopify and you can see how it looks on localhost.

# TODO
- [X] the header should act like how it acts on emperor marbles site
- [] also make that grid thing for the hero section
- [] Fix the bug where negative margin bottom is being applied on non-index pages. --> should be doable by just defining a small option and then just adding the negative margin if there is a need for it.  

## HOW TO DO


how does emperor marble do that weird effect???

if the user has scrolled as much as the header --> add shopify-section-header-hidden which does translate -100% in Y
if user has already scrolled as much as the header -> add .animate class(which defines an transition)
if user scrolled up --> remove the header hidden class so there isnt any translate -100%

THİS WAY, I dont need to CHANGE the height to make it grow

Ok did that.
