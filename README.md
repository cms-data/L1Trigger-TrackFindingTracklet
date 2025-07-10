# L1Trigger-TrackFindingTracklet

This repository contains various data files that are needed to run the extended
L1 tracking that includes displaced (triplet) seeding with the "hourglass"
&phi;-sector definition.

## Wiring and modules descriptions

### DAT format

#### Wiring

This contains the detailed wiring of the various processing and memory modules:

[wires_hourglassExtendedAllCombined.dat](wires_hourglassExtendedAllCombined.dat)

#### Processing modules

This contains the detailed list of processing modules (e.g. VMRouter,
TrackletProcessor, MatchProcessor, &hellip;):

[processingmodules_hourglassExtendedAllCombined.dat](processingmodules_hourglassExtendedAllCombined.dat)

#### Memory modules

This similarly contains the detailed list of memory modules (e.g. InputLink,
AllStubs, FullMatch, TrackletParameters, &hellip;):

[memorymodules_hourglassExtendedAllCombined.dat](memorymodules_hourglassExtendedAllCombined.dat)

### JSON format

This contains an equivalent description of the detailed wiring of the various
processing and memory modules in an easier-to-edit JSON file format. In the
near future, this will replace the DAT files listed above:

[seedWiring.json](seedWiring.json)
