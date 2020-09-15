<!DOCTYPE html>
<html>
	<head>
		<title>chart created with amCharts | amCharts</title>
		<meta name="description" content="chart created using amCharts live editor" />
		
		<!-- amCharts javascript sources -->
		<script type="text/javascript" src="https://www.amcharts.com/lib/3/amcharts.js"></script>
		<script type="text/javascript" src="https://www.amcharts.com/lib/3/serial.js"></script>
		<script type="text/javascript" src="https://www.amcharts.com/lib/3/themes/dark.js"></script>
		

		<!-- amCharts javascript code -->
		<script type="text/javascript">
			AmCharts.makeChart("chartdiv",
				{
					"type": "serial",
					"categoryField": "category",
					"startDuration": 1,
					"fontFamily": "Arial",
					"fontSize": 12,
					"handDrawScatter": 5,
					"handDrawThickness": 2,
					"theme": "dark",
					"categoryAxis": {
						"gridPosition": "start"
					},
					"trendLines": [],
					"graphs": [
						{
							"fillAlphas": 1,
							"id": "AmGraph-1",
							"title": "graph 1",
							"type": "column",
							"valueField": "graph 1"
						}
					],
					"guides": [],
					"valueAxes": [
						{
							"id": "ValueAxis-1",
							"logarithmic": true,
							"title": "Money generated in Trillions USD"
						}
					],
					"allLabels": [],
					"balloon": {},
					"titles": [
						{
							"id": "Title-1",
							"size": 15,
							"text": "Contribution of travel & tourism to Global GDP "
						}
					],
					"dataProvider": [
						{
							"category": "2014",
							"graph 1": "7.8"
						},
						{
							"category": "2015",
							"graph 1": "7.6"
						},
						{
							"category": "2016",
							"graph 1": "8.0"
						},
						{
							"category": "2017",
							"graph 1": "8.2"
						},
						{
							"category": "2018",
							"graph 1": "8.8"
						},
						{
							"category": "2019",
							"graph 1": "9.5"
						}
					]
				}
			);
		</script>
	</head>
	<body>
		<div id="chartdiv" style="width: 100%; height: 400px; background-color: #282828;" ></div>
	</body>
</html>
