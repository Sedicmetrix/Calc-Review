Given the initial-value problem $$\frac{dy}{dx}=f(x,y);\,\,y(x_0)=y_0$$
We can start at the ordered pair $(x_0,y_0)$ and approximate a solution using the algorithm $$x_n=x_{n-1}+h$$
$$y_n=y_{n-1}+h*f(x_{n-1},y_{n-1})$$
where $h=\Delta{x}$ is the step size