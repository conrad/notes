NodeJS

Built-in
  Use __dirname to get the current directory anywhere
      __filename for the 

  path
    - .join(...) 
      - useful because whatever you put in here is turned into a properly formatted path, validating & adding or removing /'s or the like where needed -- and uses \'s when in Win env
      - path.join(__dirname, 'something', 'in/', '/the', 'way/')

  RexExp
    - new RegExp(/whatever/ig)
    - .exec() - returns either null or array of info

  Buffer
    - created by default from fs.readFile or fs.readFileSync
    - stores data in binary 
    - .toString([indices]) - might be useful to read using incrementing indices for space
  
  fs
    readFileSync('full filepath'[, encoding, like 'ascii'/'utf8'])
    - utf-8 is a superset of ASCII to include char's for international


