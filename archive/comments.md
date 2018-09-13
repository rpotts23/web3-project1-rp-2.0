# Comments

## Prof notes on MP1-D

Things are moving forward well! A few things:

* Consider setting `auto` margins on left and right for `body` so that the page centers overall.
* Flexbox works such that you set it up on a parent element and as a result the direct children of that parent will tile up. This is why in your first official row all the paragraphs are tiling up. Group them in a `div` and control its width to avoid this.
* Likewise, for the features list you've set `flex-flow:row wrap` on the `li` instead of on the `ul` that is the parent/container where this is supposed to be set. Otherwise, good job controlling those elements. 
* Do you mean the main photo as in the one at the very top? If its a BG on `header` then you might need to make that element taller through adding padding or (cautiously) setting a height there.


I fixed the snapshot feature so give that another try for future work.

## Prof notes on MP1-C

Nice start on styling. I see you've also started implementing some layout work.

* Push even further to match the font sizes, leading, and weight as precisely as possible. note that you have an error on line 11 where you specify the font. You cannot set weight using the `font-family` setting. 
* Colors also have some room to further lock into sync. 

## Prof notes on MP1-B

Good markup here overall! A few notes:

* Let's use the simpler HTML5 DOCTYPE:

```html
<!DOCTYPE html>
```

* Reconsider a class such a `.list` if its on a normal list. Instead, add a class on the thing that is the exception or note that you can use further-out classes to apply styles on inner elements. So for example, you'll want to remove bullets from the `#class li` but leave normal `li` with bullets. WIth this in mind `.list` is unnecessary since you can establish styles for normal lists by just selecting `li` and remove the bullets on other more specific elements with more specific selectors such as `#class li`




## Student notes
HD: the main photo look too thin
Tablet:class tiles are not deviding into 2 groups. It looks ok, but not exactly like the comp
.lead text won't stack up on tablet, desktop, and desktop HD