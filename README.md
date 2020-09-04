# NBA-Three-Point-Research
Data Analysis on the trend of three point shots in today's NBA game.
function initializeViz() {
var placeholderDiv = document.getElementById("tableauViz");
var url = "http://public.tableau.com/views/WorldIndicators/GDPpercapita";
var options = {
 width: '600px',
 height: '600px',
 hideTabs: true,
 hideToolbar: true,
 };
viz = new tableau.Viz(placeholderDiv, url, options);
}
