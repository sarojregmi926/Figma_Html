# Figma Design to HTML CSS Website complete Tutorial ytube channel: Techinfo_yt 
https://www.youtube.com/watch?v=W4X1WRq_Zms&ab_channel=TechinfoYT

# Another nice video:
https://www.youtube.com/watch?v=AAXYX4LH6Bc&ab_channel=CodewithSloba


import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  const increment = () => {
    setCount(count + 1);
  };

  const decrement = () => {
    setCount(count - 1);
  };

  return (
    <div>
      <h2>Counter</h2>
      <button onClick={decrement}>-</button>
      <span>{count}</span>
      <button onClick={increment}>+</button>
    </div>
  );
}

export default Counter;

