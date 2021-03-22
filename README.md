### (V)ocal (O)nset (L)atency Python Package
This package was made to easily compute vocal onset latency without any specialty equipment. All that's needed is a computer and a microphone!


### Getting Started
(`pip install` coming soon)

    import volpy
    # Create Detector variable and record a single vocal onset latency time; print to csv
    det = Detector()
    det.record_vol(timout = 5)
    det.to_csv("file.csv")

### Inspired by [sebastiaan](https://forum.cogsci.nl/index.php?p=/discussion/1772/) and [Primusa](https://stackoverflow.com/questions/18406570/python-record-audio-on-detected-sound)