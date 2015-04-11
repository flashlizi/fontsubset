A font subset extraction tool using google sfntly. 

You can use it get a tiny font size, especially for webfont.

### Install

```
npm install fontsubset -g
```

**Note**: Java is required.

### Usage

```
fontsubset [options] fontFile [outputFile]
```

### Options

    -s, --string [string]  subset string to extract
    -b, --base64           output font subset in base64 format
    -h, --help             output usage information
    -V, --version          output the version number


### Examples

```
fontsubset -s 'Hello World' font/arial.ttf output/arial-subset.ttf
```


```
fontsubset -s '世界，你好！' font/微软雅黑.ttf output/微软雅黑-subset.ttf
```