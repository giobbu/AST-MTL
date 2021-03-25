# AST-MTL
Traffic forecasting is crucial in Intelligent Transportation Systems (ITS). To achieve accurate results, it is necessary to model the dynamic nature and the complex non-linear dependencies governing traffic. The goal is particularly challenging when the prediction involves more than just one traffic variable. This paper proposes a novel multi-task learning model, called AST-MTL, to perform multi-horizon predictions of the traffic flow and speed at the road network scale. The strategy combines a multilayer fully-connected neural network (FNN) and a multi-head attention mechanism to learn related tasks while improving generalization performance.  The model also includes the graph convolutional network (GCNs) and the gated recurrent unit network (GRUs)  to extract the spatial and temporal features of traffic conditions. Our experiments employ new sets of GPS data, called OBU data, to perform traffic prediction in the freeway and urban contexts. The experimental results prove our model can effectively perform multi-horizon traffic forecasting for different types of roads and outperform state-of-the-art models.
