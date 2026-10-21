
# Silicon Valley Bitcoin alert
<img src="gilfoyle.jpg"  title="silicon valley bitcoin alert">
<img src="update.png" title="console output">

# Gilfoyle-bitcoin-alert : <small>Bitcoin is Really Volatile Today </small>
## API: <a href="https://coinmarketcap.com/api/documentation/pro-api-reference/keyless-public-api/">CoinMarketCap Keyless Public API</a>
<ul>

  <li>When the previous price of a bitcoin is hit by the latest price the  program alerts playing Napalm Death mp3</li>
  <li>previous price is fetched from the alerts.txt file</li>
  <li>Latest price is fetched from the coinmarketcap api </li>
  <li>Default currency is in USD But it can be changed on the source code with (USD or whatever you like)</li>
  <li>This Api changes every 5 minute..so program checks the changes every 5 minute and display results</li>
  </ul>
 
## Installation and Running code
<p> pip install -r requirements.txt</p> 
<p> python alert.py </p>

On Windows, install FFmpeg (including `ffplay`) and ensure `ffplay` is on
`PATH`; alert audio plays without opening a media-player window. On Linux and
macOS, install `mpg123` to play alert audio.
