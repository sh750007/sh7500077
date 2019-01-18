<!DOCTYPE html>
<html>
	<head>
		<title>台北市里長選舉女性歷屆參選概況 | amCharts</title>
		<meta name="description" content="chart created using amCharts live editor" />
		
		<!-- amCharts javascript sources -->
		<script type="text/javascript" src="https://www.amcharts.com/lib/3/amcharts.js"></script>
		<script type="text/javascript" src="https://www.amcharts.com/lib/3/serial.js"></script>
		

		<!-- amCharts javascript code -->
		<script type="text/javascript">
			AmCharts.makeChart("chartdiv",
				{
					"type": "serial",
					"categoryField": "date",
					"dataDateFormat": "YYYY",
					"theme": "default",
					"categoryAxis": {
						"minPeriod": "YYYY",
						"parseDates": true
					},
					"chartCursor": {
						"enabled": true,
						"animationDuration": 0,
						"categoryBalloonDateFormat": "YYYY"
					},
					"chartScrollbar": {
						"enabled": true
					},
					"trendLines": [],
					"graphs": [
						{
							"bullet": "round",
							"id": "AmGraph-1",
							"title": "參選人",
							"valueField": "參選人"
						},
						{
							"bullet": "square",
							"id": "AmGraph-2",
							"title": "當選人",
							"valueField": "當選人"
						}
					],
					"guides": [],
					"valueAxes": [
						{
							"id": "ValueAxis-1",
							"title": "人數"
						}
					],
					"allLabels": [],
					"balloon": {},
					"legend": {
						"enabled": true,
						"useGraphSettings": true
					},
					"titles": [
						{
							"id": "Title-1",
							"size": 15,
							"text": "新北市女性里長選舉概況"
						}
					],
					"dataProvider": [
						{
							"date": "103",
							"參選人": "337",
							"當選人": "183"
						},
						{
							"date": "107",
							"參選人": "420",
							"當選人": "216"
						}
					]
				}
			);
		</script>
	</head>
	<body>
		<div id="chartdiv" style="width: 100%; height: 400px; background-color: #FFFFFF;" ></div>
	</body>
</html>
