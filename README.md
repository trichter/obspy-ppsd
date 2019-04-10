## Command line script to calculate and plot probabilistic power spectral densities with ObsPy

Download the file, make it execuatble and run it:

```
$ obspy-ppsd -h
$ obspy-ppsd add -i inventory.xml folder_with_data/*.mseed
$ obspy-pssd add folder_with_more_data/*.mseed
$ obspy-pssd plot *.npz
$ obspy-pssd timeplot 1,5,10 *.npz
$ obspy-pssd spectrogram *.npz
```