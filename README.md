> [!WARNING]
> As described in [#16](https://github.com/open-rmf/pybind11_json_vendor/issues/16) this repo should no longer be needed. You can use the [`pybind11-json-dev`](https://github.com/ros/rosdistro/pull/40223/files) key in rosdep instead.
>
> Therefore this repo is archived and will not be undergoing any more updates or releases.

# A vendor package for `pybind11_json`

This package helps bring the C++ [pybind11_json](https://github.com/pybind/pybind11_json) library into a workspace when it is not already available in the underlay. `pybind11_json` provides easily conversion between `nlohmann::json` and `py::object`.
