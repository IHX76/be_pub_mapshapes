# be_pub_mapshapes

a belgian map of municipalities by their nis code

based upon https://github.com/bmesuere/belgium-topojson -which is great, but has the lowest level as the 4rth layer, which made it unuasable with powerbi's drilldown choropleth that can only go 3 levels deep.  

using mapshaper.org, I went 'back to basics' and removed all the other layers and only kept the nis, name_fr, name_nl attributes (console commmand '-filter-fields nis,name_nl,name_fr')
