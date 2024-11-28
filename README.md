# topoplot_axeshandle
The EEGLAB function topoplot() is useful, but it has a significant limitation: it cannot specify an axes handle for plotting. 
This limitation is particularly problematic when developing an interactive GUI using MATLAB App Designer, where providing axes handles for plotting is essential.
To resolve this issue, I have introduced an 'axeshandle' option, allowing users to specify an axes handle for rendering graphics. 
Please note that this upgrade is still experimental and not all options are supported. However, it works with the default settings, which meet all my needs.
