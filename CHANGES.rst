0.2 (unreleased)
----------------

Updates
.......
- LineList.available_transitions() no longer has key argument n_max
- LineList: extra attributes for transitions added (`ion_name`, `log(w*f)`, `abundance`, `ion_correction`, `rel_strength`)
- ASCII tables with no header are required to be 4 columns or less for `io.readspec` to work
- Modify XSpectrum1D to use masked numpy arrays
- Enable hdf5 I/O  [requires h5py]
- Added .header property to XSpectrum1D (reads from .meta)
- Added XSpectrum1D.write, a generic write wrapper

Bug fixes
.........

- Fix `XSpectrum1D.from_tuple` to allow an astropy table column to
  specify wavelengths and fluxes.


0.1 (2016-01-31)
----------------

First public release.
