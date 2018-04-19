ouxinyu.github.io
=================

ouxinyu.github.io

The backward pass begins with the loss and computes the gradient with respect to the output $$\frac{\partial f_W}{\partial h}$$. The gradient with respect to the rest of the model is computed layer-by-layer through the chain rule. Layers with parameters, like the `INNER_PRODUCT` layer, compute the gradient with respect to their parameters $$\frac{\partial f_W}{\partial W_{\text{ip}}}$$ during the backward step.
