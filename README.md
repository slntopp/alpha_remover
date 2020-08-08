# Alpha Remover

## Synopsys

Not so long time ago, i was working on iOS Application and publishing it to AppStore.
After spending hours to make icons fit needed format, size and etc(means XCode accepted all them),
AppStore Connect was declining Archive because of some mysterious Error.
The actual problem was, that despite you can see it on PNG, a lot of PNGs have Aplha Layer(Transparent Layer). And even if your icon is not using transparent background(has no cutten shapes and stuff) you may need to remove Alpha properly to use it.

### Solution 1 - Convert and Reconvert

This is actually naive solution, but at least it works and won't cause any visible changes on the most of icons.
So what's it?

1. Convert every single image to JPEG
2. And then back to PNG

   ???

3. PROFIT

You can find and use this solution in this repo as [Apple Workflow](/ar.apple.workflow)

### Solution 2 - Actually cut out Alpha Layer from PNG

Coming soon.
