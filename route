const express = require('express');
const app = express();
const router = express.Router();

router.use((req,res,next) =>{
    console.log('router moddleware');
    next();
});

router.get('/user',(req,res)=>{
    res.send('User Route');
});

app.use('/api',router);
app.listen(3000, () => {
  console.log('Server running on http://localhost:3000');
});
