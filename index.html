<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="initial-scale=1,user-scalable=no,maximum-scale=1,width=device-width">
        <meta name="mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="stylesheet" href="css/leaflet.css">
        <link rel="stylesheet" href="css/L.Control.Layers.Tree.css">
        <link rel="stylesheet" href="css/L.Control.Locate.min.css">
        <link rel="stylesheet" href="css/qgis2web.css">
        <link rel="stylesheet" href="css/fontawesome-all.min.css">
        <link rel="stylesheet" href="css/leaflet.photon.css">
        <style>
        #map {
            width: 974px;
            height: 593px;
        }
        </style>
        <title></title>
    </head>
    <body>
        <div id="map">
        </div>
        <script src="js/qgis2web_expressions.js"></script>
        <script src="js/leaflet.js"></script>
        <script src="js/L.Control.Layers.Tree.min.js"></script>
        <script src="js/L.Control.Locate.min.js"></script>
        <script src="js/leaflet.rotatedMarker.js"></script>
        <script src="js/leaflet.pattern.js"></script>
        <script src="js/leaflet-hash.js"></script>
        <script src="js/Autolinker.min.js"></script>
        <script src="js/rbush.min.js"></script>
        <script src="js/labelgun.min.js"></script>
        <script src="js/labels.js"></script>
        <script src="js/leaflet.photon.js"></script>
        <script src="data/PROVETY_0.js"></script>
        <script src="data/MEDIANINCOME_1.js"></script>
        <script src="data/residuderegression_2.js"></script>
        <script src="data/clustersLISA_3.js"></script>
        <script src="data/obesity_AL_MS_TNcounties_4.js"></script>
        <script src="data/ALALIMIT_5.js"></script>
        <script src="data/MISSIPILIMIT_6.js"></script>
        <script src="data/TENESLIMIT_7.js"></script>
        <script>
        var map = L.map('map', {
            zoomControl:false, maxZoom:28, minZoom:1
        }).fitBounds([[25.54124550709647,-99.56705162889727],[43.321153756814326,-66.61516265222507]]);
        var hash = new L.Hash(map);
        map.attributionControl.setPrefix('<a href="https://github.com/qgis2web/qgis2web" target="_blank">qgis2web</a> &middot; <a href="https://leafletjs.com" title="A JS library for interactive maps">Leaflet</a> &middot; <a href="https://qgis.org">QGIS</a>');
        var autolinker = new Autolinker({truncate: {length: 30, location: 'smart'}});
        // remove popup's row if "visible-with-data"
        function removeEmptyRowsFromPopupContent(content, feature) {
         var tempDiv = document.createElement('div');
         tempDiv.innerHTML = content;
         var rows = tempDiv.querySelectorAll('tr');
         for (var i = 0; i < rows.length; i++) {
             var td = rows[i].querySelector('td.visible-with-data');
             var key = td ? td.id : '';
             if (td && td.classList.contains('visible-with-data') && feature.properties[key] == null) {
                 rows[i].parentNode.removeChild(rows[i]);
             }
         }
         return tempDiv.innerHTML;
        }
        // modify popup if contains media
        function addClassToPopupIfMedia(content, popup) {
            var tempDiv = document.createElement('div');
            tempDiv.innerHTML = content;
            var imgTd = tempDiv.querySelector('td img');
            if (imgTd) {
                var src = imgTd.getAttribute('src');
                if (/\.(jpg|jpeg|png|gif|bmp|webp|avif)$/i.test(src)) {
                    popup._contentNode.classList.add('media');
                    var img = popup._contentNode.querySelector('td img');
                    if (img) {
                        // If already loaded (cache), update immediately
                        if (img.complete && img.naturalHeight > 0) {
                            popup.update();
                        } else {
                            img.addEventListener('load', function() {
                                popup.update();
                            });
                            img.addEventListener('error', function() {
                                popup.update();
                            });
                        }
                    }
                } else if (/\.(mp3|wav|ogg|aac)$/i.test(src)) {
                    var audio = document.createElement('audio');
                    audio.controls = true;
                    audio.src = src;
                    imgTd.parentNode.replaceChild(audio, imgTd);
                    popup._contentNode.classList.add('media');
                    setTimeout(function() {
                        popup.setContent(tempDiv.innerHTML);
                        popup.update();
                    }, 10);
                } else if (/\.(mp4|webm|ogg|mov)$/i.test(src)) {
                    var video = document.createElement('video');
                    video.controls = true;
                    video.src = src;
                    video.style.width = "400px";
                    video.style.height = "300px";
                    video.style.maxHeight = "60vh";
                    video.style.maxWidth = "60vw";
                    imgTd.parentNode.replaceChild(video, imgTd);
                    popup._contentNode.classList.add('media');
                    // Aggiorna il popup quando il video carica i metadati
                    video.addEventListener('loadedmetadata', function() {
                        popup.update();
                    });
                    setTimeout(function() {
                        popup.setContent(tempDiv.innerHTML);
                        popup.update();
                    }, 10);
                } else {
                    popup._contentNode.classList.remove('media');
                }
            } else {
                popup._contentNode.classList.remove('media');
            }
        }
        var zoomControl = L.control.zoom({
            position: 'topleft'
        }).addTo(map);
        L.control.locate({locateOptions: {maxZoom: 19}}).addTo(map);
        var bounds_group = new L.featureGroup([]);
        function setBounds() {
        }
        function pop_PROVETY_0(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">fid</th>\
                        <td>' + (feature.properties['fid'] !== null ? autolinker.link(String(feature.properties['fid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">GEOID</th>\
                        <td>' + (feature.properties['GEOID'] !== null ? autolinker.link(String(feature.properties['GEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(String(feature.properties['NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATEFP</th>\
                        <td>' + (feature.properties['STATEFP'] !== null ? autolinker.link(String(feature.properties['STATEFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE</th>\
                        <td>' + (feature.properties['STATE'] !== null ? autolinker.link(String(feature.properties['STATE']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">obesity</th>\
                        <td>' + (feature.properties['obesity'] !== null ? autolinker.link(String(feature.properties['obesity']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">income</th>\
                        <td>' + (feature.properties['income'] !== null ? autolinker.link(String(feature.properties['income']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">pov_rate</th>\
                        <td>' + (feature.properties['pov_rate'] !== null ? autolinker.link(String(feature.properties['pov_rate']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">lisa_cluster</th>\
                        <td>' + (feature.properties['lisa_cluster'] !== null ? autolinker.link(String(feature.properties['lisa_cluster']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">resid</th>\
                        <td>' + (feature.properties['resid'] !== null ? autolinker.link(String(feature.properties['resid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">fitted</th>\
                        <td>' + (feature.properties['fitted'] !== null ? autolinker.link(String(feature.properties['fitted']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            var content = removeEmptyRowsFromPopupContent(popupContent, feature);
			layer.on('popupopen', function(e) {
				addClassToPopupIfMedia(content, e.popup);
			});
			layer.bindPopup(content, { maxHeight: 400 });
        }

        function style_PROVETY_0_0(feature) {
            if (feature.properties['pov_rate'] >= 4.500000 && feature.properties['pov_rate'] <= 13.700000 ) {
                return {
                pane: 'pane_PROVETY_0',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,245,240,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['pov_rate'] >= 13.700000 && feature.properties['pov_rate'] <= 16.700000 ) {
                return {
                pane: 'pane_PROVETY_0',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(252,190,165,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['pov_rate'] >= 16.700000 && feature.properties['pov_rate'] <= 18.880000 ) {
                return {
                pane: 'pane_PROVETY_0',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(251,112,80,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['pov_rate'] >= 18.880000 && feature.properties['pov_rate'] <= 22.840000 ) {
                return {
                pane: 'pane_PROVETY_0',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(211,32,32,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['pov_rate'] >= 22.840000 && feature.properties['pov_rate'] <= 38.000000 ) {
                return {
                pane: 'pane_PROVETY_0',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(103,0,13,1.0)',
                interactive: true,
            }
            }
        }
        map.createPane('pane_PROVETY_0');
        map.getPane('pane_PROVETY_0').style.zIndex = 400;
        map.getPane('pane_PROVETY_0').style['mix-blend-mode'] = 'normal';
        var layer_PROVETY_0 = new L.geoJson(json_PROVETY_0, {
            attribution: '',
            interactive: true,
            dataVar: 'json_PROVETY_0',
            layerName: 'layer_PROVETY_0',
            pane: 'pane_PROVETY_0',
            onEachFeature: pop_PROVETY_0,
            style: style_PROVETY_0_0,
        });
        bounds_group.addLayer(layer_PROVETY_0);
        map.addLayer(layer_PROVETY_0);
        function pop_MEDIANINCOME_1(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">fid</th>\
                        <td>' + (feature.properties['fid'] !== null ? autolinker.link(String(feature.properties['fid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">GEOID</th>\
                        <td>' + (feature.properties['GEOID'] !== null ? autolinker.link(String(feature.properties['GEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(String(feature.properties['NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATEFP</th>\
                        <td>' + (feature.properties['STATEFP'] !== null ? autolinker.link(String(feature.properties['STATEFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE</th>\
                        <td>' + (feature.properties['STATE'] !== null ? autolinker.link(String(feature.properties['STATE']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">obesity</th>\
                        <td>' + (feature.properties['obesity'] !== null ? autolinker.link(String(feature.properties['obesity']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">income</th>\
                        <td>' + (feature.properties['income'] !== null ? autolinker.link(String(feature.properties['income']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">pov_rate</th>\
                        <td>' + (feature.properties['pov_rate'] !== null ? autolinker.link(String(feature.properties['pov_rate']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">lisa_cluster</th>\
                        <td>' + (feature.properties['lisa_cluster'] !== null ? autolinker.link(String(feature.properties['lisa_cluster']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">resid</th>\
                        <td>' + (feature.properties['resid'] !== null ? autolinker.link(String(feature.properties['resid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">fitted</th>\
                        <td>' + (feature.properties['fitted'] !== null ? autolinker.link(String(feature.properties['fitted']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            var content = removeEmptyRowsFromPopupContent(popupContent, feature);
			layer.on('popupopen', function(e) {
				addClassToPopupIfMedia(content, e.popup);
			});
			layer.bindPopup(content, { maxHeight: 400 });
        }

        function style_MEDIANINCOME_1_0(feature) {
            if (feature.properties['income'] >= 29271.000000 && feature.properties['income'] <= 44468.600000 ) {
                return {
                pane: 'pane_MEDIANINCOME_1',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(8,48,107,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['income'] >= 44468.600000 && feature.properties['income'] <= 50383.000000 ) {
                return {
                pane: 'pane_MEDIANINCOME_1',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(41,121,185,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['income'] >= 50383.000000 && feature.properties['income'] <= 55716.400000 ) {
                return {
                pane: 'pane_MEDIANINCOME_1',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(115,178,216,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['income'] >= 55716.400000 && feature.properties['income'] <= 61944.600000 ) {
                return {
                pane: 'pane_MEDIANINCOME_1',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(200,220,240,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['income'] >= 61944.600000 && feature.properties['income'] <= 131202.000000 ) {
                return {
                pane: 'pane_MEDIANINCOME_1',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(225,255,254,1.0)',
                interactive: true,
            }
            }
        }
        map.createPane('pane_MEDIANINCOME_1');
        map.getPane('pane_MEDIANINCOME_1').style.zIndex = 401;
        map.getPane('pane_MEDIANINCOME_1').style['mix-blend-mode'] = 'normal';
        var layer_MEDIANINCOME_1 = new L.geoJson(json_MEDIANINCOME_1, {
            attribution: '',
            interactive: true,
            dataVar: 'json_MEDIANINCOME_1',
            layerName: 'layer_MEDIANINCOME_1',
            pane: 'pane_MEDIANINCOME_1',
            onEachFeature: pop_MEDIANINCOME_1,
            style: style_MEDIANINCOME_1_0,
        });
        bounds_group.addLayer(layer_MEDIANINCOME_1);
        map.addLayer(layer_MEDIANINCOME_1);
        function pop_residuderegression_2(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">fid</th>\
                        <td>' + (feature.properties['fid'] !== null ? autolinker.link(String(feature.properties['fid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">GEOID</th>\
                        <td>' + (feature.properties['GEOID'] !== null ? autolinker.link(String(feature.properties['GEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(String(feature.properties['NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATEFP</th>\
                        <td>' + (feature.properties['STATEFP'] !== null ? autolinker.link(String(feature.properties['STATEFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE</th>\
                        <td>' + (feature.properties['STATE'] !== null ? autolinker.link(String(feature.properties['STATE']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">obesity</th>\
                        <td>' + (feature.properties['obesity'] !== null ? autolinker.link(String(feature.properties['obesity']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">income</th>\
                        <td>' + (feature.properties['income'] !== null ? autolinker.link(String(feature.properties['income']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">pov_rate</th>\
                        <td>' + (feature.properties['pov_rate'] !== null ? autolinker.link(String(feature.properties['pov_rate']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">lisa_cluster</th>\
                        <td>' + (feature.properties['lisa_cluster'] !== null ? autolinker.link(String(feature.properties['lisa_cluster']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">resid</th>\
                        <td>' + (feature.properties['resid'] !== null ? autolinker.link(String(feature.properties['resid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">fitted</th>\
                        <td>' + (feature.properties['fitted'] !== null ? autolinker.link(String(feature.properties['fitted']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            var content = removeEmptyRowsFromPopupContent(popupContent, feature);
			layer.on('popupopen', function(e) {
				addClassToPopupIfMedia(content, e.popup);
			});
			layer.bindPopup(content, { maxHeight: 400 });
        }

        function style_residuderegression_2_0(feature) {
            if (feature.properties['resid'] >= -6.291137 && feature.properties['resid'] <= -2.194948 ) {
                return {
                pane: 'pane_residuderegression_2',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(5,113,176,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['resid'] >= -2.194948 && feature.properties['resid'] <= -0.762419 ) {
                return {
                pane: 'pane_residuderegression_2',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(146,197,222,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['resid'] >= -0.762419 && feature.properties['resid'] <= 0.489546 ) {
                return {
                pane: 'pane_residuderegression_2',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(247,235,230,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['resid'] >= 0.489546 && feature.properties['resid'] <= 2.125832 ) {
                return {
                pane: 'pane_residuderegression_2',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(244,165,130,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['resid'] >= 2.125832 && feature.properties['resid'] <= 7.734851 ) {
                return {
                pane: 'pane_residuderegression_2',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(202,0,32,1.0)',
                interactive: true,
            }
            }
        }
        map.createPane('pane_residuderegression_2');
        map.getPane('pane_residuderegression_2').style.zIndex = 402;
        map.getPane('pane_residuderegression_2').style['mix-blend-mode'] = 'normal';
        var layer_residuderegression_2 = new L.geoJson(json_residuderegression_2, {
            attribution: '',
            interactive: true,
            dataVar: 'json_residuderegression_2',
            layerName: 'layer_residuderegression_2',
            pane: 'pane_residuderegression_2',
            onEachFeature: pop_residuderegression_2,
            style: style_residuderegression_2_0,
        });
        bounds_group.addLayer(layer_residuderegression_2);
        map.addLayer(layer_residuderegression_2);
        function pop_clustersLISA_3(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">fid</th>\
                        <td>' + (feature.properties['fid'] !== null ? autolinker.link(String(feature.properties['fid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">GEOID</th>\
                        <td>' + (feature.properties['GEOID'] !== null ? autolinker.link(String(feature.properties['GEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(String(feature.properties['NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATEFP</th>\
                        <td>' + (feature.properties['STATEFP'] !== null ? autolinker.link(String(feature.properties['STATEFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE</th>\
                        <td>' + (feature.properties['STATE'] !== null ? autolinker.link(String(feature.properties['STATE']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">obesity</th>\
                        <td>' + (feature.properties['obesity'] !== null ? autolinker.link(String(feature.properties['obesity']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">income</th>\
                        <td>' + (feature.properties['income'] !== null ? autolinker.link(String(feature.properties['income']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">pov_rate</th>\
                        <td>' + (feature.properties['pov_rate'] !== null ? autolinker.link(String(feature.properties['pov_rate']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">lisa_cluster</th>\
                        <td>' + (feature.properties['lisa_cluster'] !== null ? autolinker.link(String(feature.properties['lisa_cluster']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">resid</th>\
                        <td>' + (feature.properties['resid'] !== null ? autolinker.link(String(feature.properties['resid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">fitted</th>\
                        <td>' + (feature.properties['fitted'] !== null ? autolinker.link(String(feature.properties['fitted']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            var content = removeEmptyRowsFromPopupContent(popupContent, feature);
			layer.on('popupopen', function(e) {
				addClassToPopupIfMedia(content, e.popup);
			});
			layer.bindPopup(content, { maxHeight: 400 });
        }

        function style_clustersLISA_3_0(feature) {
            switch(String(feature.properties['lisa_cluster'])) {
                case 'High-High':
                    return {
                pane: 'pane_clustersLISA_3',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(189,0,38,1.0)',
                interactive: true,
            }
                    break;
                case 'High-Low':
                    return {
                pane: 'pane_clustersLISA_3',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(230,47,33,1.0)',
                interactive: true,
            }
                    break;
                case 'Low-High':
                    return {
                pane: 'pane_clustersLISA_3',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(248,108,49,1.0)',
                interactive: true,
            }
                    break;
                case 'Low-Low':
                    return {
                pane: 'pane_clustersLISA_3',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(253,166,73,1.0)',
                interactive: true,
            }
                    break;
                case 'Not significant':
                    return {
                pane: 'pane_clustersLISA_3',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(254,214,109,1.0)',
                interactive: true,
            }
                    break;
                default:
                    return {
                pane: 'pane_clustersLISA_3',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,255,178,1.0)',
                interactive: true,
            }
                    break;
            }
        }
        map.createPane('pane_clustersLISA_3');
        map.getPane('pane_clustersLISA_3').style.zIndex = 403;
        map.getPane('pane_clustersLISA_3').style['mix-blend-mode'] = 'normal';
        var layer_clustersLISA_3 = new L.geoJson(json_clustersLISA_3, {
            attribution: '',
            interactive: true,
            dataVar: 'json_clustersLISA_3',
            layerName: 'layer_clustersLISA_3',
            pane: 'pane_clustersLISA_3',
            onEachFeature: pop_clustersLISA_3,
            style: style_clustersLISA_3_0,
        });
        bounds_group.addLayer(layer_clustersLISA_3);
        map.addLayer(layer_clustersLISA_3);
        function pop_obesity_AL_MS_TNcounties_4(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">fid</th>\
                        <td>' + (feature.properties['fid'] !== null ? autolinker.link(String(feature.properties['fid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">GEOID</th>\
                        <td>' + (feature.properties['GEOID'] !== null ? autolinker.link(String(feature.properties['GEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(String(feature.properties['NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATEFP</th>\
                        <td>' + (feature.properties['STATEFP'] !== null ? autolinker.link(String(feature.properties['STATEFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE</th>\
                        <td>' + (feature.properties['STATE'] !== null ? autolinker.link(String(feature.properties['STATE']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">obesity</th>\
                        <td>' + (feature.properties['obesity'] !== null ? autolinker.link(String(feature.properties['obesity']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">income</th>\
                        <td>' + (feature.properties['income'] !== null ? autolinker.link(String(feature.properties['income']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">pov_rate</th>\
                        <td>' + (feature.properties['pov_rate'] !== null ? autolinker.link(String(feature.properties['pov_rate']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">lisa_cluster</th>\
                        <td>' + (feature.properties['lisa_cluster'] !== null ? autolinker.link(String(feature.properties['lisa_cluster']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">resid</th>\
                        <td>' + (feature.properties['resid'] !== null ? autolinker.link(String(feature.properties['resid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">fitted</th>\
                        <td>' + (feature.properties['fitted'] !== null ? autolinker.link(String(feature.properties['fitted']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            var content = removeEmptyRowsFromPopupContent(popupContent, feature);
			layer.on('popupopen', function(e) {
				addClassToPopupIfMedia(content, e.popup);
			});
			layer.bindPopup(content, { maxHeight: 400 });
        }

        function style_obesity_AL_MS_TNcounties_4_0(feature) {
            if (feature.properties['obesity'] >= 28.700000 && feature.properties['obesity'] <= 38.460000 ) {
                return {
                pane: 'pane_obesity_AL_MS_TNcounties_4',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,255,178,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['obesity'] >= 38.460000 && feature.properties['obesity'] <= 39.920000 ) {
                return {
                pane: 'pane_obesity_AL_MS_TNcounties_4',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(254,204,92,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['obesity'] >= 39.920000 && feature.properties['obesity'] <= 41.900000 ) {
                return {
                pane: 'pane_obesity_AL_MS_TNcounties_4',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(253,141,60,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['obesity'] >= 41.900000 && feature.properties['obesity'] <= 44.200000 ) {
                return {
                pane: 'pane_obesity_AL_MS_TNcounties_4',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(240,59,32,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['obesity'] >= 44.200000 && feature.properties['obesity'] <= 54.000000 ) {
                return {
                pane: 'pane_obesity_AL_MS_TNcounties_4',
                stroke: false, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(189,0,38,1.0)',
                interactive: true,
            }
            }
        }
        map.createPane('pane_obesity_AL_MS_TNcounties_4');
        map.getPane('pane_obesity_AL_MS_TNcounties_4').style.zIndex = 404;
        map.getPane('pane_obesity_AL_MS_TNcounties_4').style['mix-blend-mode'] = 'normal';
        var layer_obesity_AL_MS_TNcounties_4 = new L.geoJson(json_obesity_AL_MS_TNcounties_4, {
            attribution: '',
            interactive: true,
            dataVar: 'json_obesity_AL_MS_TNcounties_4',
            layerName: 'layer_obesity_AL_MS_TNcounties_4',
            pane: 'pane_obesity_AL_MS_TNcounties_4',
            onEachFeature: pop_obesity_AL_MS_TNcounties_4,
            style: style_obesity_AL_MS_TNcounties_4_0,
        });
        bounds_group.addLayer(layer_obesity_AL_MS_TNcounties_4);
        map.addLayer(layer_obesity_AL_MS_TNcounties_4);
        function pop_ALALIMIT_5(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">fid</th>\
                        <td>' + (feature.properties['fid'] !== null ? autolinker.link(String(feature.properties['fid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATEFP</th>\
                        <td>' + (feature.properties['STATEFP'] !== null ? autolinker.link(String(feature.properties['STATEFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTYFP</th>\
                        <td>' + (feature.properties['COUNTYFP'] !== null ? autolinker.link(String(feature.properties['COUNTYFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTYNS</th>\
                        <td>' + (feature.properties['COUNTYNS'] !== null ? autolinker.link(String(feature.properties['COUNTYNS']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">AFFGEOID</th>\
                        <td>' + (feature.properties['AFFGEOID'] !== null ? autolinker.link(String(feature.properties['AFFGEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">GEOID</th>\
                        <td>' + (feature.properties['GEOID'] !== null ? autolinker.link(String(feature.properties['GEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(String(feature.properties['NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAMELSAD</th>\
                        <td>' + (feature.properties['NAMELSAD'] !== null ? autolinker.link(String(feature.properties['NAMELSAD']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STUSPS</th>\
                        <td>' + (feature.properties['STUSPS'] !== null ? autolinker.link(String(feature.properties['STUSPS']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE_NAME</th>\
                        <td>' + (feature.properties['STATE_NAME'] !== null ? autolinker.link(String(feature.properties['STATE_NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">LSAD</th>\
                        <td>' + (feature.properties['LSAD'] !== null ? autolinker.link(String(feature.properties['LSAD']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">ALAND</th>\
                        <td>' + (feature.properties['ALAND'] !== null ? autolinker.link(String(feature.properties['ALAND']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">AWATER</th>\
                        <td>' + (feature.properties['AWATER'] !== null ? autolinker.link(String(feature.properties['AWATER']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            var content = removeEmptyRowsFromPopupContent(popupContent, feature);
			layer.on('popupopen', function(e) {
				addClassToPopupIfMedia(content, e.popup);
			});
			layer.bindPopup(content, { maxHeight: 400 });
        }

        function style_ALALIMIT_5_0() {
            return {
                pane: 'pane_ALALIMIT_5',
                opacity: 1,
                color: 'rgba(0,0,0,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fillOpacity: 0,
                interactive: true,
            }
        }
        map.createPane('pane_ALALIMIT_5');
        map.getPane('pane_ALALIMIT_5').style.zIndex = 405;
        map.getPane('pane_ALALIMIT_5').style['mix-blend-mode'] = 'normal';
        var layer_ALALIMIT_5 = new L.geoJson(json_ALALIMIT_5, {
            attribution: '',
            interactive: true,
            dataVar: 'json_ALALIMIT_5',
            layerName: 'layer_ALALIMIT_5',
            pane: 'pane_ALALIMIT_5',
            onEachFeature: pop_ALALIMIT_5,
            style: style_ALALIMIT_5_0,
        });
        bounds_group.addLayer(layer_ALALIMIT_5);
        map.addLayer(layer_ALALIMIT_5);
        function pop_MISSIPILIMIT_6(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">fid</th>\
                        <td>' + (feature.properties['fid'] !== null ? autolinker.link(String(feature.properties['fid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATEFP</th>\
                        <td>' + (feature.properties['STATEFP'] !== null ? autolinker.link(String(feature.properties['STATEFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTYFP</th>\
                        <td>' + (feature.properties['COUNTYFP'] !== null ? autolinker.link(String(feature.properties['COUNTYFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTYNS</th>\
                        <td>' + (feature.properties['COUNTYNS'] !== null ? autolinker.link(String(feature.properties['COUNTYNS']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">AFFGEOID</th>\
                        <td>' + (feature.properties['AFFGEOID'] !== null ? autolinker.link(String(feature.properties['AFFGEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">GEOID</th>\
                        <td>' + (feature.properties['GEOID'] !== null ? autolinker.link(String(feature.properties['GEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(String(feature.properties['NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAMELSAD</th>\
                        <td>' + (feature.properties['NAMELSAD'] !== null ? autolinker.link(String(feature.properties['NAMELSAD']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STUSPS</th>\
                        <td>' + (feature.properties['STUSPS'] !== null ? autolinker.link(String(feature.properties['STUSPS']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE_NAME</th>\
                        <td>' + (feature.properties['STATE_NAME'] !== null ? autolinker.link(String(feature.properties['STATE_NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">LSAD</th>\
                        <td>' + (feature.properties['LSAD'] !== null ? autolinker.link(String(feature.properties['LSAD']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">ALAND</th>\
                        <td>' + (feature.properties['ALAND'] !== null ? autolinker.link(String(feature.properties['ALAND']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">AWATER</th>\
                        <td>' + (feature.properties['AWATER'] !== null ? autolinker.link(String(feature.properties['AWATER']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            var content = removeEmptyRowsFromPopupContent(popupContent, feature);
			layer.on('popupopen', function(e) {
				addClassToPopupIfMedia(content, e.popup);
			});
			layer.bindPopup(content, { maxHeight: 400 });
        }

        function style_MISSIPILIMIT_6_0() {
            return {
                pane: 'pane_MISSIPILIMIT_6',
                opacity: 1,
                color: 'rgba(0,0,0,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fillOpacity: 0,
                interactive: true,
            }
        }
        map.createPane('pane_MISSIPILIMIT_6');
        map.getPane('pane_MISSIPILIMIT_6').style.zIndex = 406;
        map.getPane('pane_MISSIPILIMIT_6').style['mix-blend-mode'] = 'normal';
        var layer_MISSIPILIMIT_6 = new L.geoJson(json_MISSIPILIMIT_6, {
            attribution: '',
            interactive: true,
            dataVar: 'json_MISSIPILIMIT_6',
            layerName: 'layer_MISSIPILIMIT_6',
            pane: 'pane_MISSIPILIMIT_6',
            onEachFeature: pop_MISSIPILIMIT_6,
            style: style_MISSIPILIMIT_6_0,
        });
        bounds_group.addLayer(layer_MISSIPILIMIT_6);
        map.addLayer(layer_MISSIPILIMIT_6);
        function pop_TENESLIMIT_7(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">fid</th>\
                        <td>' + (feature.properties['fid'] !== null ? autolinker.link(String(feature.properties['fid']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATEFP</th>\
                        <td>' + (feature.properties['STATEFP'] !== null ? autolinker.link(String(feature.properties['STATEFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTYFP</th>\
                        <td>' + (feature.properties['COUNTYFP'] !== null ? autolinker.link(String(feature.properties['COUNTYFP']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTYNS</th>\
                        <td>' + (feature.properties['COUNTYNS'] !== null ? autolinker.link(String(feature.properties['COUNTYNS']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">AFFGEOID</th>\
                        <td>' + (feature.properties['AFFGEOID'] !== null ? autolinker.link(String(feature.properties['AFFGEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">GEOID</th>\
                        <td>' + (feature.properties['GEOID'] !== null ? autolinker.link(String(feature.properties['GEOID']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(String(feature.properties['NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">NAMELSAD</th>\
                        <td>' + (feature.properties['NAMELSAD'] !== null ? autolinker.link(String(feature.properties['NAMELSAD']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STUSPS</th>\
                        <td>' + (feature.properties['STUSPS'] !== null ? autolinker.link(String(feature.properties['STUSPS']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE_NAME</th>\
                        <td>' + (feature.properties['STATE_NAME'] !== null ? autolinker.link(String(feature.properties['STATE_NAME']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">LSAD</th>\
                        <td>' + (feature.properties['LSAD'] !== null ? autolinker.link(String(feature.properties['LSAD']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">ALAND</th>\
                        <td>' + (feature.properties['ALAND'] !== null ? autolinker.link(String(feature.properties['ALAND']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">AWATER</th>\
                        <td>' + (feature.properties['AWATER'] !== null ? autolinker.link(String(feature.properties['AWATER']).replace(/'/g, '\'').toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            var content = removeEmptyRowsFromPopupContent(popupContent, feature);
			layer.on('popupopen', function(e) {
				addClassToPopupIfMedia(content, e.popup);
			});
			layer.bindPopup(content, { maxHeight: 400 });
        }

        function style_TENESLIMIT_7_0() {
            return {
                pane: 'pane_TENESLIMIT_7',
                opacity: 1,
                color: 'rgba(35,35,35,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fillOpacity: 0,
                interactive: true,
            }
        }
        map.createPane('pane_TENESLIMIT_7');
        map.getPane('pane_TENESLIMIT_7').style.zIndex = 407;
        map.getPane('pane_TENESLIMIT_7').style['mix-blend-mode'] = 'normal';
        var layer_TENESLIMIT_7 = new L.geoJson(json_TENESLIMIT_7, {
            attribution: '',
            interactive: true,
            dataVar: 'json_TENESLIMIT_7',
            layerName: 'layer_TENESLIMIT_7',
            pane: 'pane_TENESLIMIT_7',
            onEachFeature: pop_TENESLIMIT_7,
            style: style_TENESLIMIT_7_0,
        });
        bounds_group.addLayer(layer_TENESLIMIT_7);
        map.addLayer(layer_TENESLIMIT_7);
        setBounds();
        resetLabels([layer_PROVETY_0,layer_MEDIANINCOME_1,layer_residuderegression_2,layer_clustersLISA_3,layer_obesity_AL_MS_TNcounties_4]);
        map.on("zoomend", function(){
            resetLabels([layer_PROVETY_0,layer_MEDIANINCOME_1,layer_residuderegression_2,layer_clustersLISA_3,layer_obesity_AL_MS_TNcounties_4]);
        });
        map.on("layeradd", function(){
            resetLabels([layer_PROVETY_0,layer_MEDIANINCOME_1,layer_residuderegression_2,layer_clustersLISA_3,layer_obesity_AL_MS_TNcounties_4]);
        });
        map.on("layerremove", function(){
            resetLabels([layer_PROVETY_0,layer_MEDIANINCOME_1,layer_residuderegression_2,layer_clustersLISA_3,layer_obesity_AL_MS_TNcounties_4]);
        });
        </script>
    </body>
</html>
