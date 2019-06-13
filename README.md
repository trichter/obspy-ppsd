## Command line script to calculate and plot probabilistic power spectral densities with ObsPy

Download the file, make it executable and run it:

```
$ obspy-ppsd -h
$ obspy-ppsd add -i inventory.xml folder_with_data/*.mseed
$ obspy-ppsd add folder_with_more_data/*.mseed
$ obspy-ppsd plot *.npz
$ obspy-ppsd timeplot 1,5,10 *.npz
$ obspy-ppsd spectrogram *.npz
```