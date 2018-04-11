# Adversarial

This repo contains code for our 2018 NAACL paper entitled "EMR Coding with Semi-Parametric Multi-Head Matching Networks".

**Note:** Examples of the data format can be found in the data/ folder.

## Usage
### Training

```
usage: train_match.py [-h] [--num_epochs NUM_EPOCHS] [--num_models NUM_MODELS]
                      [--word_vectors WORD_VECTORS] [--labels LABELS]
                      [--checkpoint_dir CHECKPOINT_DIR]
                      [--checkpoint_name CHECKPOINT_NAME]
                      [--hidden_state HIDDEN_STATE]
                      [--learn_embeddings LEARN_EMBEDDINGS] [--min_df MIN_DF]
                      [--lr LR] [--penalty PENALTY] [--dropout DROPOUT]
                      [--lr_decay LR_DECAY] [--minibatch_size MINIBATCH_SIZE]
                      [--val_minibatch_size VAL_MINIBATCH_SIZE]
                      [--model_type MODEL_TYPE] [--train_data_X TRAIN_DATA_X]
                      [--val_data_X VAL_DATA_X] [--seed SEED]
                      [--grad_clip GRAD_CLIP]
                      [--cnn_conv_size CNN_CONV_SIZE [CNN_CONV_SIZE ...]]
                      [--num_feat_maps NUM_FEAT_MAPS] [--num_att NUM_ATT]
                      [--num_support NUM_SUPPORT]

Train Neural Network.

optional arguments:
  -h, --help            show this help message and exit
  --num_epochs NUM_EPOCHS
                        Number of updates to make.
  --num_models NUM_MODELS
                        Number of updates to make.
  --word_vectors WORD_VECTORS
                        Word vecotors filepath.
  --labels LABELS       All Labels.
  --checkpoint_dir CHECKPOINT_DIR
                        Checkpoint directory.
  --checkpoint_name CHECKPOINT_NAME
                        Checkpoint File Name.
  --hidden_state HIDDEN_STATE
                        hidden layer size.
  --learn_embeddings LEARN_EMBEDDINGS
                        Learn Embedding Parameters.
  --min_df MIN_DF       Min word count.
  --lr LR               Learning Rate.
  --penalty PENALTY     Regularization Parameter.
  --dropout DROPOUT     Dropout Value.
  --lr_decay LR_DECAY   Learning Rate Decay.
  --minibatch_size MINIBATCH_SIZE
                        Mini-batch Size.
  --val_minibatch_size VAL_MINIBATCH_SIZE
                        Val Mini-batch Size.
  --model_type MODEL_TYPE
                        Neural Net Architecutre.
  --train_data_X TRAIN_DATA_X
                        Training Data.
  --val_data_X VAL_DATA_X
                        Validation Data.
  --seed SEED           Random Seed.
  --grad_clip GRAD_CLIP
                        Gradient Clip Value.
  --cnn_conv_size CNN_CONV_SIZE [CNN_CONV_SIZE ...]
                        CNN Covolution Sizes (widths)
  --num_feat_maps NUM_FEAT_MAPS
                        Number of CNN Feature Maps.
  --num_att NUM_ATT     Number of Heads.
  --num_support NUM_SUPPORT
                        Number nearest neighbors to sample for each input
                        instance.
```

## Acknowledgements

> Anthony Rios and Ramakanth Kavuluru. "EMR Coding with Semi-Parametric Multi-Head Matching Networks". NAACL 2018

```
@inproceedings{arios2018emrmatch,
  title={EMR Coding with Semi-Parametric Multi-Head Matching Networks},
  author={Rios, Anthony and Kavuluru, Ramakanth},
  booktitle={Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies},
  year={2018}
}
```

Written by Anthony Rios (anthonymrios at gmail dot com)