```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

## Discovery Logic

```mermaid
flowchart TD
  A [ Deploy to production] --> B { Is it Friday? };
  B -- Yes --> C [Do not deploy];
  B -- No --> D [Run deploy];
  C ----> E [Enjoy your weekend];
  C ----> E [Enjoy your weekend];
```
