# Data Visualization

- Graphs and plots are efficient way to communicate data.
- _matplotlib_ is a powerful most used Python package for 2D-graphics.

### IPython
> enhanced interactive Python shell that has lots of interesting features including named inputs and outputs, access to shell commands, improved debugging and much more

### pylab 
> provides a convenient interface to the matplotlib object-oriented plotting library


### Simple plot
- Example:
    > import numpy as np

    X = np.linspace(-np.pi, np.pi, 256, endpoint=True)
    C, S = np.cos(X), np.sin(X)

    **Changing colors and line widths**
    ...
    plt.figure(figsize=(10,6), dpi=80)
    plt.plot(X, C, color="blue", linewidth=2.5, linestyle="-")
    plt.plot(X, S, color="red",  linewidth=2.5, linestyle="-")
    ...
    **Setting limits**
    ...
    plt.xlim(X.min()*1.1, X.max()*1.1)
    plt.ylim(C.min()*1.1, C.max()*1.1)
    ...
    **Setting tick labels**
    ...
    plt.xticks( [-np.pi, -np.pi/2, 0, np.pi/2, np.pi])
    plt.yticks([-1, 0, +1])
    ...
    ...
    plt.xticks([-np.pi, -np.pi/2, 0, np.pi/2, np.pi],
        [r'$-\pi$', r'$-\pi/2$', r'$0$', r'$+\pi/2$', r'$+\pi$'])

    plt.yticks([-1, 0, +1],
        [r'$-1$', r'$0$', r'$+1$'])
    ...
    **Moving spines**
    ...
    ax = plt.gca()
    ax.spines['right'].set_color('none')
    ax.spines['top'].set_color('none')
    ax.xaxis.set_ticks_position('bottom')
    ax.spines['bottom'].set_position(('data',0))
    ax.yaxis.set_ticks_position('left')
    ax.spines['left'].set_position(('data',0))
    ..
    **Adding a legend**
    ...
    plt.plot(X, C, color="blue", linewidth=2.5, linestyle="-", label="cosine")
    plt.plot(X, S, color="red",  linewidth=2.5, linestyle="-", label="sine")

    plt.legend(loc='upper left', frameon=False)
    ...

### Notes
- Animation can be done using matplotlib, especially after launching the new version being.
- **Types of Plots**:
  - Regular Plot (Plot lines/markers)
  - Scatter Plot
  - Bar Plot
  - Contour Plot
  - IMSHOW (Image showing)
  - Quiver Plot
  - Pie Chart
  - Grid
  - Multi-Plot
  - Polar-Axis
  - 3D Plots
  - Text