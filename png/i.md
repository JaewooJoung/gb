# jpeg to png 
for file in *.jpg; do magick "$file" "${file%.jpg}.png"; done
