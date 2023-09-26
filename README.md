# python Code to download Fonts
import requests <br>
response = requests.get(" Font Url below ") <br>
font_data = response.content <br>
with open("font.TTF", "wb") as font_file:<br>
  font_file.write(font_data)
  
# Fonts Url
Font Mooli : https://raw.githubusercontent.com/PopoolaIbrahim/Fonts-Collection-/main/font_mooli.TTF
            
