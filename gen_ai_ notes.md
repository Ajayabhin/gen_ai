# UI PAGE

## Preamble overide:
- just an agent description.

## Tempreature:
- increses the entropy of the probablities of the elements.

## Top K:
- selects the top k elements for the top probability.

## Top P
- selects top n number of elements that whose total % adds ap to p%.

## Frequency penality
- penalises the element by the times it has appeared .

    `more number of times it apprears more  the penality it gets `

## Presence penality 
- penalises the element even if it apperars once.


# INPUT
## Embedding:
- numreical representation `(vectors)` of text .
- these vectors are used for 
    - classification
    - clustering
    - to search it with similar vectors to find the matching files or stuff from internet.

## prompt:
- input to the model.

## in-context learning:
- giving step  by step (procedures)  instructions as prompt.

## k shot prompting:
- giving k similar examples in the prompt.

## prompt format:
- some fromat are use in some models to get specific output.

## Chain-of-thoughts:
- providing a example to the prompt which includes reasoning step (how to calulate or logical steps that we want the ai to do).
