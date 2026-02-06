## Observed Issues

- Initial load slow due to backend cold start
- Messages lag during high frequency emits
- Entire message list re-rendering on new message

## Tools Used
- console.time / console.timeEnd
- React DevTools (highlight re-renders)
- Network tab (payload size)
