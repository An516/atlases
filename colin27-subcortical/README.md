Colin-27 Subcortical Atlases
============================

The atlases in this folder are based on the Colin-27 Average Brain:

    http://www.bic.mni.mcgill.ca/ServicesAtlases/Colin27

When using these atlases, please cite:

    Chakravarty MM, Bertrand G, Hodge CP, Sadikot AF, Collins DL. The creation
    of a brain atlas for image guided neurosurgery using serial histological
    data. Neuroimage. 2006;30(2):359-76.


Whole thalamus, Globus Pallidus and Striatum
--------------------------------------------

label file: labels/thalamus-globus_pallidus-striatum.mnc

Label: 1 - left striatum
Label: 2 - left globus pallidus
Label: 3 - left thalamus
Label: 4 - right striatum
Label: 5 - right globus pallidus
Label: 6 - right thalamus

surfaces:
  - thalamus:
    - surfaces/thalamus-left.obj
    - surfaces/thalamus-right.obj
  - globus pallidus:
    - surfaces/globus_pallidus-left.obj
    - surfaces/globus_pallidus-right.obj
  - striatum:
    - surfaces/striatum-left.obj
    - surfaces/striatum-right.obj

Subdivisions of the striatum
----------------------------

label file: labels/striatum-subdivisions.mnc
```
Label: 100 - left nucleus accumbens / ventral striatum
Label: 101 - left precommissural putamen
Label: 102 - left precommissural caudate
Label: 104 - left postcommissural caudate
Label: 105 - left postcommissural putamen
Label: 110 - right nucleus accumbens / ventral striatum
Label: 111 - right precommissural putamen
Label: 112 - right precommissural caudate
Label: 114 - right postcommissural caudate
Label: 115 - right postcommissural putamen
```

Surface labels:
  - surfaces/striatum-subdivisions-left-labels.txt
  - surfaces/striatum-subdivisions-right-labels.txt

Subdivisions of the thalamus
----------------------------

label file: labels/thalamus-subdivisions.mnc
```
Label: 1   - left lateral geniculate nucleus (LGN)
Label: 2   - left medial geniculate nucleus (MGN)
Label: 3   - left anterior nuclei
Label: 4   - left central nuclei
Label: 5   - left lateral dorsal
Label: 6   - left lateral posterior
Label: 7   - left medial dorsal
Label: 8   - left pulvinar
Label: 9   - left ventral anterior nucleus
Label: 10  - left ventral lateral nucleus
Label: 11  - left ventral posterior nucleus
Label: 21  - right lateral geniculate nucleus (LGN)
Label: 22  - right medial geniculate nucleus (MGN)
Label: 23  - right anterior nuclei
Label: 24  - right central nuclei
Label: 25  - right lateral dorsal
Label: 26  - right lateral posterior
Label: 27  - right medial dorsal
Label: 28  - right pulvinar
Label: 29  - right ventral anterior nucleus
Label: 30  - right ventral lateral nucleus
Label: 31  - right ventral posterior nucleus
```

Surface labels:
  - surfaces/thalamus-subdivisions-left-labels.txt
  - surfaces/thalamus-subdivisions-right-labels.txt
