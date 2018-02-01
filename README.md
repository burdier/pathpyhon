# pathpyhon
The easy way to deal with file paths on Windows, Mac and Linux, la manera correcta de trabajar con rutas en windows , mac y linux


The Better Solution: Python 3’s pathlib!

Python 3.4 introduced a new standard library for dealing with files and paths called pathlib — and it’s great!

To use it, you just pass a path or filename into a new Path() object using forward slashes and it handles the rest:


from pathlib import Path

data_folder = Path("source_data/text_files/")

file_to_open = data_folder / "raw_data.txt"

f = open(file_to_open)

print(f.read())
