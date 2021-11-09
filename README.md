# PBI-CV-Afonso-Feliciano


Link para visualizar o meu Currículo desenvolvido em Power BI: https://afonsofeliciano.github.io/PBI-CV-Afonso-Feliciano/

<!DOCTYPE html>
<html>
<body>
    <p align="center">
	<iframe width="1280" height="720" src="https://app.powerbi.com/view?r=eyJrIjoiNWI3ZWQxNTAtNWVmYi00ZjA0LWEwODgtNmIwMGViOGRlMTRhIiwidCI6ImY2OWYzNjJmLTYzYmQtNDFiOS04NDEzLWQxZmVlNzg1NmZmNyJ9&pageName=ReportSection10d439867880993540ed" frameborder="0" allowFullScreen="true"></iframe>
</p>
    <script>
        fetch('https://api.github.com/repos/agalea91/crypto-monetary-base/contents/charts/relative_coin_supply_pct_estimates.html')
            .then(function(response) {
                return response.json();
            }).then(function(data) {
                iframe = document.getElementById('github-iframe');
                iframe.src = 'data:text/html;base64,' + encodeURIComponent(data['content']);
            });
    </script>
</body>
</html>


