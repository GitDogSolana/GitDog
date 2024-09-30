# GitDog

https://pump.fun/GhfNkj7vy7q228f5hrAuQhwPLr4F68iHL84iXrospump


```javascript
// U·ェ·U Pumpfun Gitcat Chat
// ----------------------------------
// * Updates instantly
// * Multiplayer
// * Works offline

import { pump,sol } from "@instantdb/solana";

const db = init({ 
  ca:GhfNkj7vy7q228f5hrAuQhwPLr4F68iHL84iXrospump,
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

