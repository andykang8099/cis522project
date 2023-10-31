# File Descriptions
- cafa3.csv contanins the raw data downloaded from the CAFA website.
- data_cleand contains the cafa3.csv and interation data from STRING and UnitProt after cleaning 
- models_with_embeddings.ibynb contains the embedding and contact map generation as well as ML, MLP, CNN, and GAT models 
- Advanced_Model final version.ibynb contains the code implemented on BiLSTM, BiLSTM with attention mechanism, GCN, Ensemble models
- advanced_model_final_version.py is the Python source code of Advanced_Model final version.ibynb
- small_embeddings.pkl contains the pickled dictionary of {protein id : ESM2 embedding} to load into our experiments so they don't have to be generated every time
- small_embeddings.csv contains the csv version of the dictionary of {protein id : ESM2 embedding} to load into our experiments so they don't have to be generated every time
- gat_data_list.npy contains the data for the GAT, which includes the contact map data
- basic_models_final_version.ipynb contains the code implemented on CNN, RNN(GRU), and AE-MLP hybrid model
- basic_models_final_version.py is the Python source code of basic_models_final_version.ipynb
- Data integration.ipynb shows the steps of processing UnitProt data and CAFA data. It also contains the session of extracting interaction data from STRING API and mergeing all the datasets
- basic_models_first_version.ipynb is the implementation of CNN, AE+MLP, Random Forest, GCN, and LSTM on the protein sequence using single label prediction(functional class)

The models within the files should be organized under headings.