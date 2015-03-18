# Hooks
| Name | args | Description |
|------|------|-------------|
| `global.defaults` | `defaults` | Passes the global defaults prior to merging with args and chart-specific defaults |
| `global.before_init` | `args` | Called before initializing a chart. Allows pre-processing of the arguments passed into `MG.data_graphic`. |
| `x_axis.process_min_max` | `args`, `min_x`, `max_x` | Called after calculating the min and max values for the X axis |
| `y_axis.process_min_max` | `args`, `min_y`, `max_y` | Called after calculating the min and max values for the Y axis |
| `line.after_init` | `lineChart` - chart descriptor | Called after intializing the chart |
| `line.after_rollover` | `args` | Called after setting up the rollover |
