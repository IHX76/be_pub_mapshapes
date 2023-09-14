# be_pub_mapshapes

a belgian map of municipalities by their nis code (as of 2019)

based upon https://github.com/bmesuere/belgium-topojson -which is great, but is multi-layered and has the lowest level as the 4rth layer, which made it unuasable with powerbi's drilldown choropleth that can only go 3 levels deep.  

using mapshaper.org, I went 'back to basics' and removed all the other layers and only kept the nis, name_fr, name_nl attributes (console command '-filter-fields nis,name_nl,name_fr')


