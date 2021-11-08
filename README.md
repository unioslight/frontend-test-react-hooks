# frontend-test-react-hooks

To do - convert the below into a working project.

```jsx
import React, { useEffect, useState } from "react";

export const Checkbox = ({ id, onChange, isChecked = false, ...otherProps }) => {
  
  //Add missing code

  return (
    <input
      id={id}
      type="checkbox"
      checked={isCheckedInternal}
      {...otherProps}
    />
  );
};

Checkbox.displayName = "Checkbox";
```

The above React checkbox component must be completed.

It must have internal state for the purpose of developing styles and demonstrating the component in a component library. 

It must also optionally handle hoisted state from a parent component. To do this, it must update the parent component's state on change if a handler is provided. This onChange handler requires an event as an argument.

The internal value must also update if the parent component's state changes (for example, when resetting a form).
