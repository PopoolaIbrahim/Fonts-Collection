# Fonts-Collection-

# python Code to download Fonts
response = requests.get(" Font Url below ")
font_data = response.content
with open("font.TTF", "wb") as font_file:
  font_file.write(font_data)
  
# Fonts Url
Font Mooli : https://raw.githubusercontent.com/PopoolaIbrahim/Fonts-Collection-/main/font_mooli.TTF
            
