---
layout: post
title: Fourteen.
---

As I was figuring out how I wanted to get the sound on the map, I discovered a way to actually generate random intervals of coordinates all along the path I had already input onto My Maps on Google. I go through it step by step [here](https://ottlovestories.wordpress.com/mapping-a-love-song/), but I wanted to include the code that method generate here as part of my paradata. 

### map one

```
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Document>
    <name>Directions from Willard St. to The Horticulture Building</name>
    <Style id="icon-1899-DB4436-nodesc-normal">
      <IconStyle>
        <color>ff3644db</color>
        <scale>1</scale>
        <Icon>
          <href>http://www.gstatic.com/mapspro/images/stock/503-wht-blank_maps.png</href>
        </Icon>
        <hotSpot x="32" xunits="pixels" y="64" yunits="insetPixels"/>
      </IconStyle>
      <LabelStyle>
        <scale>0</scale>
      </LabelStyle>
      <BalloonStyle>
        <text><![CDATA[<h3>$[name]</h3>]]></text>
      </BalloonStyle>
    </Style>
    <Style id="icon-1899-DB4436-nodesc-highlight">
      <IconStyle>
        <color>ff3644db</color>
        <scale>1</scale>
        <Icon>
          <href>http://www.gstatic.com/mapspro/images/stock/503-wht-blank_maps.png</href>
        </Icon>
        <hotSpot x="32" xunits="pixels" y="64" yunits="insetPixels"/>
      </IconStyle>
      <LabelStyle>
        <scale>1</scale>
      </LabelStyle>
      <BalloonStyle>
        <text><![CDATA[<h3>$[name]</h3>]]></text>
      </BalloonStyle>
    </Style>
    <StyleMap id="icon-1899-DB4436-nodesc">
      <Pair>
        <key>normal</key>
        <styleUrl>#icon-1899-DB4436-nodesc-normal</styleUrl>
      </Pair>
      <Pair>
        <key>highlight</key>
        <styleUrl>#icon-1899-DB4436-nodesc-highlight</styleUrl>
      </Pair>
    </StyleMap>
    <Style id="line-1267FF-5000-nodesc-normal">
      <LineStyle>
        <color>ffff6712</color>
        <width>5</width>
      </LineStyle>
      <BalloonStyle>
        <text><![CDATA[<h3>$[name]</h3>]]></text>
      </BalloonStyle>
    </Style>
    <Style id="line-1267FF-5000-nodesc-highlight">
      <LineStyle>
        <color>ffff6712</color>
        <width>7.5</width>
      </LineStyle>
      <BalloonStyle>
        <text><![CDATA[<h3>$[name]</h3>]]></text>
      </BalloonStyle>
    </Style>
    <StyleMap id="line-1267FF-5000-nodesc">
      <Pair>
        <key>normal</key>
        <styleUrl>#line-1267FF-5000-nodesc-normal</styleUrl>
      </Pair>
      <Pair>
        <key>highlight</key>
        <styleUrl>#line-1267FF-5000-nodesc-highlight</styleUrl>
      </Pair>
    </StyleMap>
    <Placemark>
      <name>Directions from Willard St. to The Horticulture Building</name>
      <styleUrl>#line-1267FF-5000-nodesc</styleUrl>
      <LineString>
        <tessellate>1</tessellate>
        <coordinates>
          -75.68002,45.39182,0
          -75.67991,45.39171,0
          -75.67998,45.39168,0
          -75.68061,45.39142,0
          -75.68068,45.3914,0
          -75.68075,45.39138,0
          -75.68082,45.39136,0
          -75.68148,45.3919,0
          -75.68167,45.39182,0
          -75.68148,45.3919,0
          -75.68174,45.39211,0
          -75.68202,45.39235,0
          -75.6823,45.39263,0
          -75.68251,45.39287,0
          -75.68256,45.39292,0
          -75.68272,45.39312,0
          -75.68286,45.39331,0
          -75.68295,45.39345,0
          -75.68303,45.39357,0
          -75.68343,45.39428,0
          -75.68377,45.39493,0
          -75.68416,45.39562,0
          -75.6843,45.39588,0
          -75.68436,45.39599,0
          -75.68442,45.3961,0
          -75.68443,45.39612,0
          -75.68444,45.39613,0
          -75.68448,45.3962,0
          -75.68465,45.3965,0
          -75.68466,45.39652,0
          -75.68472,45.39662,0
          -75.68474,45.39665,0
          -75.68482,45.39679,0
          -75.68488,45.39688,0
          -75.68495,45.397,0
          -75.68501,45.39712,0
          -75.68529,45.39763,0
          -75.6853,45.39766,0
          -75.68531,45.39767,0
          -75.68532,45.39769,0
          -75.68533,45.39776,0
          -75.6854,45.3979,0
          -75.68544,45.39797,0
          -75.68589,45.3988,0
          -75.68605,45.39911,0
          -75.68613,45.39925,0
          -75.6862,45.39937,0
          -75.68631,45.39952,0
          -75.68641,45.3996,0
          -75.68652,45.39975,0
          -75.68657,45.39983,0
          -75.68661,45.39989,0
          -75.68672,45.40009,0
          -75.68693,45.40045,0
          -75.68708,45.40072,0
          -75.68693,45.40045,0
          -75.68672,45.40009,0
          -75.68661,45.39989,0
          -75.68657,45.39983,0
          -75.68652,45.39975,0
          -75.68641,45.3996,0
          -75.68631,45.39952,0
          -75.6862,45.39937,0
          -75.6858,45.39952,0
          -75.68521,45.39977,0
          -75.68503,45.39983,0
          -75.68411,45.4002,0
          -75.68401,45.40024,0
          -75.68308,45.40062,0
          -75.68272,45.40077,0
        </coordinates>
      </LineString>
    </Placemark>
    <Placemark>
      <name>Willard St.</name>
      <styleUrl>#icon-1899-DB4436-nodesc</styleUrl>
      <Point>
        <coordinates>
          -75.6800169,45.391824,0
        </coordinates>
      </Point>
    </Placemark>
    <Placemark>
      <name><![CDATA[Patty's]]></name>
      <styleUrl>#icon-1899-DB4436-nodesc</styleUrl>
      <Point>
        <coordinates>
          -75.6816737,45.3918169,0
        </coordinates>
      </Point>
    </Placemark>
    <Placemark>
      <name>Aparment</name>
      <styleUrl>#icon-1899-DB4436-nodesc</styleUrl>
      <Point>
        <coordinates>
          -75.6834298,45.3942823,0
        </coordinates>
      </Point>
    </Placemark>
    <Placemark>
      <name><![CDATA[Irene's]]></name>
      <styleUrl>#icon-1899-DB4436-nodesc</styleUrl>
      <Point>
        <coordinates>
          -75.6870769,45.4007162,0
        </coordinates>
      </Point>
    </Placemark>
    <Placemark>
      <name>The Horticulture Building</name>
      <styleUrl>#icon-1899-DB4436-nodesc</styleUrl>
      <Point>
        <coordinates>
          -75.6827185,45.4007678,0
        </coordinates>
      </Point>
    </Placemark>
  </Document>
</kml>
```
