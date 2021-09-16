# Goals
Host an on-prem draw.io server with collaborative editing and integration

# Status
  1. [X] Add convergence dependencies via npm
  2. [X] Preliminary integration
  3. [] Resolve integration issue

# running
  1. Run the convergence docker image on the default port
     `docker run -p "8000:80" --name convergence convergencelabs/convergence-omnibus`
  2. Clone this repo
  3. run `npm install`
  4. run `npm start`
  5. visit http://localhost/?dev=1 from browser
