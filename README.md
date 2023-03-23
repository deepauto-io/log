# Log

logrus encapsulated log library.

# Example

```golang
s.Logger.
	WithField("error", err.Error()).
	WithField("url", src.URL).
	Info("Failed to retrieve database version")
```
