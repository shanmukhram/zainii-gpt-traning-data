# zainii-gpt-traning-data
all the data trained on complex English and generative procedural transformer model.

all the changes done and things included:-

tokenization, train/val split

data loader: batches of chunks of data

baseline:- bigram language model, loss, generation

training the bigram model

built:-  "self-attention"

version 1: averaging past context with for loops, the weakest form of aggregation

self-attention: matrix multiply as weighted aggregation

version 2: used matrix multiply

version 3: added softmax

positional encoding

crux

note 1: attention as communication 
note 2: attention has no notion of space, operates over sets
note 3: there is no communication across batch dimension
note 4: encoder blocks vs. decoder blocks
note 5: attention vs. self-attention vs. cross-attention
note 6: "scaled" self-attention. why divide by sqrt(head_size)
built the Transformer

a single self-attention block to zainii's - network


multi-headed self-attention

feedforward layers of transformer block


 residual connections
 
 
layernorm (and its relationship to our previous batchnorm)

scaled up the model! creating a few variables. added dropout
Notes on Transformer












