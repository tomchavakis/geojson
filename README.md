# :hammer: [![release](https://badgen.net/github/release/tomchavakis/geojson)](https://github.com/tomchavakis/geojson/releases/latest) [![GoDoc](https://godoc.org/github.com/tomchavakis/geojson?status.svg)](https://godoc.org/github.com/tomchavakis/geojson) [![GitHub license](https://badgen.net/github/license/tomchavakis/geojson)](https://github.com/tomchavakis/geojson/blob/main/LICENSE) [![Go Report Card](https://goreportcard.com/badge/github.com/tomchavakis/geojson)](https://goreportcard.com/report/github.com/tomchavakis/geojson)

# GeoJSON 

GeoJSON is a GoLang library that implements the [GeoJSON](https://geojson.org/) format specification


## Usage


## GeoJSON Objects

This library implements the following [GeoJSON Objects](https://datatracker.ietf.org/doc/html/rfc7946#section-3):


Point
```go
point := geometry.NewPoint(lat,lng)
```

```go
point := geometry.Point{
		Lat: 50.0,
		Lng: 30.0,
	}
```
- MultiPoint

```go
multipoint := geometry.NewPoint(lat,lng)
```

```go
multipoint := geometry.Point{
		Lat: 50.0,
		Lng: 30.0,
	}
```

- LineString
- MultiLineString
- Polygon
- MultiPolygon
- Feature
- FeatureCollection
- Geometry
- GeometryCollection



## turf-go
You can also use the library turf-go which is an implementation of the [turf.js](https://turfjs.org/) library in GoLang.