///// Common variables /////
env.git_repo_name="git@github.com:pseudo/XXXXX" // update this value as created in Step 9 above
env.git_id="XXXXXXXXXXXXXXXXX"  // update this value as created in Step 9 above

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
