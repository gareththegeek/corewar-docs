# Parser API

The API exposes the following functions and pubsub events:

## parse(redcode: string): IParseResult

Parse a redcode document and return an IParseResult which consists of the tokenised program and any associated messages.

## serialise(tokens: IToken[]): string

Serialises the array of tokens to a single, human readable string.