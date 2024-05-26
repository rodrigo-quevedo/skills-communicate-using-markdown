# Markdown tutorial


![Image of Yaktocat](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/f3946f08-4c6a-48e7-9a20-df76535fdcf8/d9toltf-4455ec45-27d7-416f-bbb7-ab964e0efbf5.jpg/v1/fill/w_1032,h_774,q_70,strp/minimal_nodejs_wallpaper_by_synetcon_d9toltf-pre.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MTIwMCIsInBhdGgiOiJcL2ZcL2YzOTQ2ZjA4LTRjNmEtNDhlNy05YTIwLWRmNzY1MzVmZGNmOFwvZDl0b2x0Zi00NDU1ZWM0NS0yN2Q3LTQxNmYtYmJiNy1hYjk2NGUwZWZiZjUuanBnIiwid2lkdGgiOiI8PTE2MDAifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.hmyNJ4N4dAofdjFF0JXLqf4f2rZ0291-mXc4Z8DNZrQ)


Node hello word example:

``` javascript
const http = require('node:http')

http.createServer( (req, res) => {
  res.end('Server response OK')
})
.listen(3000, ()=>{console.log('Server started at http://localhost:3000')})
```
