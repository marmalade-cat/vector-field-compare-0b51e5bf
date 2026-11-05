VectorFieldCompare

A minimal client-side prototype that imports CSV or JSON time-series with timestamps and 3D vectors (module pose, magnetometer, sun vector), aligns by time, visualizes 2D projections and per-axis plots, and exports synchronized CSV. No server, no dependencies. Use the file picker or drag files onto the page.

Input format notes:
- CSV: header row with columns: timestamp, type, x, y, z. "type" is a short label (pose, mag, sun).
- JSON: array of objects with {timestamp, type, x, y, z}.

This is a prototype for debugging and exhibit prep; interpretation of fields is up to the user.

License: public domain sample code.