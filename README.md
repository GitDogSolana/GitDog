
# GitDog

https://pump.fun/79zmusJy2PPFevzF9GTjV5pYwrzfUBzguSkWNNK9pump


```javascript
// U·ェ·U Moonshot Gitcat Chat
// ----------------------------------
// * Updates instantly
// * Multiplayer
// * Works offline

import { pump,sol } from "@instantdb/solana";

const db = init({ 
  ca:79zmusJy2PPFevzF9GTjV5pYwrzfUBzguSkWNNK9pump,
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
