# Changelog

## simtrial-rs 0.1.1

### Maintenance

- Updated GitHub repository name to `simtrial-rs` (#5).

## simtrial-rs 0.1.0

### New features

- Ported piecewise exponential sampler from the R and Python implementations,
  exposing `PiecewiseExponential` with validated construction,
  inverse CDF support, and RNG-backed sampling (#3).

### Testing

- Added fixture-based regression tests aligned with the original R outputs
  plus property-style integration tests covering error handling,
  reproducibility, and inverse-CDF behavior (#3).
