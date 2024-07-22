# MyFirstDocument

This is some demo documentation

## You can create bullet points and nested bullet points

- First Point
- Second Point
  - A first point within a point
  - A second point within a point
    - Third time is like a charm!

## You can also work with numbered lists
<!-- THIS ONLY WORKS ON TECHDOCS (BACKSTAGE) -->
1. First Level Item One
2. First Level Item Two
  1. Second Level Item One
  2. Second Level Item Two
    2. Third Level Item One

## You can do Mermaid Diagrams
```kroki-mermaid
sequenceDiagram
    Alice->>Bob: Hello Bob, how are you ?
    Bob->>Alice: Fine, thank you. And you?
    create participant Carl
    Alice->>Carl: Hi Carl!
    create actor D as Donald
    Carl->>D: Hi!
    destroy Carl
    Alice-xCarl: We are too many
    destroy Bob
    Bob->>Alice: I agree
```