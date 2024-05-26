# Markdown tutorial


![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


Node hello word example:

const http = require('node:http')

http.createServer( (req, res) => {
  res.end('Server response OK')
})
.listen(3000, ()=>{console.log('Server started at http://localhost:3000')})
