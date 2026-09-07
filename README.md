import * as React from 'react';
import Stack from '@mui/material/Stack';
import IconButton from '@mui/material/IconButton';
import AlarmIcon from '@mui/icons-material/Alarm';
import AddShoppingCartIcon from '@mui/icons-material/AddShoppingCart';

export default function AccessibleButtons() {
  return (
    <Stack direction="row" spacing={1}>
      <IconButton aria-label="set alarm" color="secondary">
        <AlarmIcon />
      </IconButton>
      <IconButton color="primary" aria-label="add item to shopping cart">
        <AddShoppingCartIcon />
      </IconButton>
    </Stack>
  );
}