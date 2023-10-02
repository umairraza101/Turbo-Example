# README

This in a Sample Project to use Turbo Drive, Turbo Frames and Turbo Stream. You can learn more about this Project from [HotRails](https://www.hotrails.dev/turbo-rails/turbo-frames-and-turbo-streams). Some Important rules are ...

* Turbo Frames are independent pieces of a web page that can be appended, prepended, replaced, or removed without a complete page refresh and writing a single line of JavaScript!

* When clicking on a link within a Turbo Frame, if there is a frame with the same id on the target page, Turbo will replace the content of the Turbo Frame of the source page with the content of the Turbo Frame of the target page.

* When clicking on a link within a Turbo Frame, if there is no Turbo Frame with the same id on the target page, Turbo will remove the content of the Turbo Frame from the source page and log an error.

* When using the "_top" keyword, the URL of the page changes to the URL of the target page, which is another difference from when using a regular Turbo Frame.

# The Turbo Stream format
The turbo_stream helper responds to the following methods.

* Remove a Turbo Frame
`turbo_stream.remove`
* Insert a Turbo Frame at the beginning/end of a list
`turbo_stream.append`
`turbo_stream.prepend`

* Insert a Turbo Frame before/after another Turbo Frame

`turbo_stream.before`
`turbo_stream.after`

* Replace or update the content of a Turbo Frame

`turbo_stream.update`
`turbo_stream.replace`
