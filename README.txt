Build ePub
==========

zip -X wealth_of_networks.epub mimetype
zip -rg wealth_of_networks.epub META-INF -x \*.DS_Store
zip -rg wealth_of_networks.epub OPS -x \*.DS_Store