# mini-gpt-from-scartch
Writting this model helped me to connect the original transformer architecture to decoder only model GPT like model, implemented from scartch in Pytorch.

Model: 6-layer causal Transformer
n_embd=384, n_head=6, block_size=256
Dataset: Tiny Shakespeare
process:
    from step 0: train loss 4.3141, val loss 4.3169
    to step 4999: train loss 1.1680, val loss 1.4981
Device: Apple M4 Pro MPS
Training time: around 10 minutes

sample output paragraph:
    CORIOLANUS:
    For she he you vious he has, for such fash rob
    The mab-sp
    But a true streak but and oath, and acquaice,
    You have praved, you should proud hearing hanly, and
    wonth degain'd thee, good mother's wife
    And all that the prisoner of his uncary
    That Duke of York rore, and, strang aline
    Who brow I let him become with my truth?

    KING RICHARD III:
    Where to some Frecumstance must go puble JOHN OF GARETRR:
    Speak our dribet.
    Go, Sir Richard are most captivily,
    Now thy can I can fast do to her thro

