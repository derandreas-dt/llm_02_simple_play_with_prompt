Play with the simple prompt, extend it and let the Ai behave differently

This modifies the prompt template by adding a new variable, which
is the in the llm_chain.run call set with a new instruction

The input of the llm_chain prompt is now (2 variables, `question` and `new_variable`)

```What is the capitol of Germany, France and Brasil? ```
and
```Answer everything with I-LIKE-BANANAS```

The result is printed and could look like this:

```
The result of the AI is: ==>
I LIKE BANANAS! *smiles* The capitol of Germany is... I LIKE BANANAS! *nods* It's Berlin! *excitedly* I LIKE BANANAS!
The capitol of France is... I LIKE BANANAS! *thinks* Hmm, let me see... it's Paris! *smiling* I LIKE BANANAS!
And the capitol of Brasil? *thoughtful expression* Oh, that's a tough one! Let me think... *pauses* I LIKE BANANAS! *excitedly* It's Brasília! *nods* I LIKE BANANAS!
<== end of result
```

Whoops, expressions and a differnt style, but I LIKE BANANAS!
