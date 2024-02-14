# GNN-based Preference Modeling for Fake News Detection - Analysis and Modification of a Novel Approach

## PROJECT DESCRIPTION:

This project investigates the use of Graph Neural Network (GNN) frameworks for fake news detection while considering both Exogenous and Endogenous Features. The project comprises two parts: Modifying GraphSAGE and exploring alternative GNN frameworks. In the first part, GraphSAGE is modified with different Multi-Layer Perceptron (MLP) configurations and evaluated on GossipCop and Politifact datasets. The results indicate that increasing MLP layers can improve performance. The second part examines the replacement of GraphSAGE with Graph Attention Network (GAT) and Graph Isomorphism Network (GIN) on the same datasets. Our findings suggest that GAT and GIN may not be suitable for these tasks and datasets, as they show no significant improvement compared to the baseline model. Overall, the study provides insights into the effectiveness of various GNN frameworks for fake news detection.

## Folder Descriptions: 

## GAT Folder:
Contains implementations of the Graph Attention Network as the Graph Encoder and BERT and Content as the Textual Encoders. The Models are implemented on both the Gossipcop as well as the Politifact Datasets. 

## GIN Folder:
Contains implementations of the Graph Isomorphic Network as the Graph Encoder and BERT and Content as the Textual Encoders. The Models are implemented on both the Gossipcop as well as the Politifact Datasets. 

## GRAPHSAGE_GOSSIPCOP Folder: 
Contains 3 Proposed Modifications on the UPFD Baseline Model using GraphSAGE as the Graph Encoder and BERT and Content as the Textual Encoders. The models are implemented on the GossipCop Dataset. 

## GRAPHSAGE_CONTENT Folder: 
Contains 3 Proposed Modifications on the UPFD Baseline Model using GraphSAGE as the Graph Encoder and BERT and Content as the Textual Encoders. The model is implemented on the Content Dataset. 

## PLOTS Folder: 
Consists of Plots for different combination of Graph( GIN and GAT) and Text Encoders for both the Politifact and Gossipcop Datasets.

