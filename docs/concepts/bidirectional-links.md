# Bidirectional Links

## Connections That Go Both Ways

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas porttitor congue massa. Fusce posuere, magna sed pulvinar ultricies, purus lectus malesuada libero, sit amet commodo magna eros quis urna.

## The Problem with One-Way Links

The World Wide Web is built on unidirectional links. When page A links to page B:

- B has no knowledge of being linked from A
- If A changes its URL, the link breaks
- There's no built-in way to see what links to a given page

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ac faucibus odio. Vestibulum neque massa, scelerisque sit amet ligula eu, congue molestie mi. Praesent ut varius sem. Nullam at porttitor arcu, nec lacinia nisi.

### How Bidirectional Links Solve This

In Xanadu's system of bidirectional linking:

1. All links are stored in a central registry
2. Both documents maintain awareness of the connection
3. Links cannot break because they use content addressing
4. Navigation is possible in both directions

!!! example "Practical Example"
    When Document A links to Document B in a bidirectional system:
    
    - Document B knows it's linked from Document A
    - Users viewing B can see and navigate to all documents that link to it
    - If either document moves, the link remains intact

## Lorem Ipsum Technical Implementation

Duis vel nibh at velit scelerisque suscipit. Curabitur turpis. Vestibulum suscipit nulla quis orci. Fusce ac felis sit amet ligula pharetra condimentum. Maecenas egestas arcu quis ligula mattis placerat.

```typescript
interface BidirectionalLink {
  sourceDocId: string;
  targetDocId: string;
  sourceRange?: [number, number];
  targetRange?: [number, number];
  metadata: {
    created: Date;
    creator: string;
    type: "reference" | "quote" | "annotation";
  };
}
```

Suspendisse in justo eu magna luctus suscipit. Sed lectus. Integer euismod lacus luctus magna. Quisque cursus, metus vitae pharetra auctor, sem massa mattis sem, at interdum magna augue eget diam.