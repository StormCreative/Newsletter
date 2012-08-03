# Newsletter
So this is the email template I use for creating our email campaigns.

## Instructions

To get started, clone this repo locally. Then open up `index.html` and update the title so it reads `Client-name Email Newsletter`. Next, make a find and replace for `#link` and replace all with the client name. Be sure the client name matches it's case study url hosted on the Storm website. For instance, to link to `stormcreative.co.uk/case_study/title/vox-empire`, the replace text would be `vox-empire`.

## Inserting content
Normally, the content you will insert will be;
- A title - for the words that need to be emphasised you will need to wrap these in a `<span>brand red</span>`
- Image - The image will need to be exported and placed within the images folder. Please add an alt tag (`alt="Explain the image"`) for when images aren't loaded.
- Content - Usually just 1 paragraph, but in the case of multiple paragraphs you're need to copy the entire `<p>` including the `<a>` with all it's styles.

## Adding new blocks
Find the first `<td>` element that has a class of `section`. I've put a html comment in above the parent `<tr>` which is what you will need to copy and paste to insert a new block.

## Lastly
Before uploading, optimise the image folder by dragging it onto [ImageOptim](http://imageoptim.com/ "Download the mac app"). Once optimised you can then compress the folder.

Now your ready to upload and test the template! Have fun :)

Yours sincerely,
Fewdog