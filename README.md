bitmap2stl
==========

Command-line script that takes a bitmap file and converts it into a 3D printable .STL file, suitable for most 3D printers.

## Requirements
* [potrace](http://potrace.sourceforge.net/) - PotraceTM is a tool for tracing bitmap graphics and outputting them as an encapsulated PostScript file (EPS)
* [pstoedit](http://www.pstoedit.net/) - translates PostScript and PDF files into vector formats
* [OpenSCAD](http://www.openscad.org/) - creates 3D solid CAD objects
* Operating system based on Linux

If you are a [Homebrew](http://brew.sh/) user you can also install *porace* and *pstoedit* via the package manager.

## Making the script executable
By default not every file on your computer is executable. This is a very good security feature but requires modifucations to the permissions to run the script from the command line. From within the context of the directory housing the script type the following command: 
```bash
chmod u+x bitmap2stl
```

## Using the script
Execute the script against a file by calling it like so: 
```bash
./my_shell_script /path/to/file.bmp
```

