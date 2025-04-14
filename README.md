# TradingView
How to embed TrendingView Charts in Notion
This is a widget for Notion App

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Widget do TradingView</title>
</head>
<body>
  <!-- Widget do TradingView -->
  <div class="tradingview-widget-container">
    <div id="tradingview_12345"></div>
    <script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
    <script type="text/javascript">
      new TradingView.widget({
        "width": 980,
        "height": 610,
        "symbol": "NASDAQ:AAPL",
        "interval": "D",
        "timezone": "Etc/UTC",
        "theme": "light",
        "style": "1",
        "locale": "br",
        "toolbar_bg": "#f1f3f6",
        "enable_publishing": false,
        "allow_symbol_change": true,
        "container_id": "tradingview_12345"
      });
    </script>
  </div>
</body>
</html>
