
# GitDog

https://pump.fun/H4d53sCutRSYDX5J6SefscZn1usH8LpBWZCsFdZnpump


```javascript
// U·ェ·U Moonshot Gitcat Chat
// ----------------------------------
// * Updates instantly
// * Multiplayer
// * Works offline

import { pump,sol } from "@instantdb/solana";

const db = init({ 
  ca:H4d53sCutRSYDX5J6SefscZn1usH8LpBWZCsFdZnpump,
});

function Chat() {
  // 1. Read
  const { isLoading, error, data } = db.useQuery({
    messages: {},
  });

  // 2. Write
  const addMessage = (message) => {
    db.transact(tx.messages[id()].update(message));
  };

  // 3. Render!
  return <UI data={data} onAdd={addMessage} />;
}
```
