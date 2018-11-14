
This repository currently provides a link to some of the modelling constraints introduced in--

Kar, K., Kubilius, J., Schmidt, K. M., Issa, E. B., & DiCarlo, J. J. (2018). Evidence that recurrent circuits are critical to the ventral stream's execution of core object recognition behavior. bioRxiv, 354753.

You can download the .h5 file from the location below:
https://www.dropbox.com/s/9syejz1wwbtcw31/dataset.h5?dl=1

Once you download the dataset.h5 file, 
please check it using matlab (python users can also use this file) in the following way.
```
>>h5disp('dataset.h5')
```
```
HDF5 dataset.h5 
Group '/' 
    Dataset 'i1' 
        Size:  1320x1
        MaxSize:  1320x1
        Datatype:   H5T_IEEE_F64LE (double)
        ChunkSize:  []
        Filters:  none
        FillValue:  0.000000
    Dataset 'images' 
        Size:  256x256x3x1320
        MaxSize:  256x256x3x1320
        Datatype:   H5T_IEEE_F64LE (double)
        ChunkSize:  []
        Filters:  none
        FillValue:  0.000000
    Dataset 'obj' 
        Size:  1320x1
        MaxSize:  1320x1
        Datatype:   H5T_IEEE_F64LE (double)
        ChunkSize:  []
        Filters:  none
        FillValue:  0.000000
    Dataset 'ost' 
        Size:  1320x1
        MaxSize:  1320x1
        Datatype:   H5T_IEEE_F64LE (double)
        ChunkSize:  []
        Filters:  none
        FillValue:  0.000000
```
