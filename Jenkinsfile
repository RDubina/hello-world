///// Common variables /////
env.git_repo_name="git@github.com:RDubina/hello-world.git" // update this value as created in Step 9 above
env.git_id="0a3f6e19-6534-4e52-9f12-a2142efbe638"  // update this value as created in Step 9 above

node("master")
{

// STAGE is a labeled block.
stage 'CI Build'

//##########################################################
// SCM is a special variable which instructs the CHECKOUT step to clone the specific revision which triggered this Pipeline
//##########################################################
checkout scm

// Below code will run the Build steps for a given application
sh '''
echo " This is a CI build Step"
###### Specify your application specific Build Steps Below ####################
###### For instance refer below build steps for node.js Application #######
# npm install
# npm run webpack
####################################################################

'''

// STAGE is a labeled block.
