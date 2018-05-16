# D3 Visualizations

This repo contains some useful D3.js visualizations

## Run a Local Server (if you have data files to load)

Some html files require loading external files. It works as expected when the files are placed online via FTP or SSH. However, if you try to view them locally, you see some kind of "cross-origin" errors in console. The solution to this is to view them using what's called a local web server. In this section I'm sharing instructions for setting up a quick Python local web server. 

In terminal, you can type:

```python
python -m SimpleHTTPServer
```

Or if you are using Python 3, type:

```python
python -m http.server
```

You can find more options [here](https://github.com/processing/p5.js/wiki/Local-server) (e.g. using Node, PHP, ...)