# Log

logrus encapsulated log library.


# install

```golang
go get github.com/workpieces/log
```

# Example

```golang
s.Logger.
	WithField("error", err.Error()).
	WithField("url", src.URL).
	Info("Failed to retrieve database version")
```
