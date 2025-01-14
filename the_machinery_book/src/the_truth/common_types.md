# Common Types

The Truth comes with several useful common types. You can find them in the `the_truth_types.h` ([API Documentation]({{docs}}foundation/the_truth_types.h.html#structtm_the_truth_common_types_api)).



| Macro                                                        | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [`TM_TT_TYPE__BOOL`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__bool) /[`TM_TT_TYPE_HASH__BOOL`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__bool) | The first property contains the value.                       |
| [`TM_TT_TYPE__UINT32_T`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__uint32_t) /[`TM_TT_TYPE_HASH__UINT32_T`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__uint32_t) | The first property contains the value.                       |
| [`TM_TT_TYPE__UINT64_T`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__uint64_t) /[`TM_TT_TYPE_HASH__UINT64_T`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__uint64_t) | The first property contains the value.                       |
| [`TM_TT_TYPE__FLOAT`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__float) /[`TM_TT_TYPE_HASH__FLOAT`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__float) | The first property contains the value.                       |
| [`TM_TT_TYPE__DOUBLE`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__double) /[`TM_TT_TYPE_HASH__DOUBLE`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__double) | The first property contains the value.                       |
| [`TM_TT_TYPE__STRING`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__string) /[`TM_TT_TYPE_HASH__STRING`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__string) | The first property contains the value.                       |
| [`TM_TT_TYPE__VEC2`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__vec2) /[`TM_TT_TYPE_HASH__VEC2`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__vec2) | The first property contains the x value and the second the y value. |
| [`TM_TT_TYPE__VEC3`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__vec3) /[`TM_TT_TYPE_HASH__VEC3`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__vec3) | The first property contains the x value and the second the y value and the third the z value. |
| [`TM_TT_TYPE__VEC4`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__vec4) /[`TM_TT_TYPE_HASH__VEC4`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__vec4) | The first property contains the x value and the second the y value and the third the z value while the last one contains the w value. |
| [`TM_TT_TYPE__POSITION`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__position) /[`TM_TT_TYPE_HASH__POSITION`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__position) | Same as `vec4`.                                              |
| [`TM_TT_TYPE__ROTATION`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__rotation) /[`TM_TT_TYPE_HASH__ROTATION`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__rotation) | Based on a `vec4`. Used to represent the rotation of a object via quaternions. |
| [`TM_TT_TYPE__SCALE`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__scale) /[`TM_TT_TYPE_HASH__SCALE`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__scale) | Same as `vec3.`                                              |
| [`TM_TT_TYPE__COLOR_RGB`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__color_rgb) /[`TM_TT_TYPE_HASH__COLOR_RGB`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__color_rgb) | Represents a RGB colour.                                     |
| [`TM_TT_TYPE__COLOR_RGBA`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__color_rgba) /[`TM_TT_TYPE_HASH__COLOR_RGBA`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__color_rgba) | Represents a RGBA colour.                                    |
| [`TM_TT_TYPE__RECT`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__rect) /[`TM_TT_TYPE_HASH__RECT`]({{docs}}foundation/the_truth_types.h.html#tm_tt_type__rect) | The first property contains the x value and the second the y value and the third the width value while the last one contains the height value. |

There is a helper API to handle all of these types in a easy way, to reduce the boilerplate code: `tm_the_truth_common_types_api`. 

> **Note:** There is a list of all Truth Types the Engine comes with available on our [API Documentation]({{docs}}truth_types.html)
