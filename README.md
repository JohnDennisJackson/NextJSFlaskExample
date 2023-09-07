# To run local

## Create and activate the environment
1. Open a cmd prompt 
2. Navigate to the root of this project (same directory that contained this file)
3. Run 'conda env create -f conda_env.yml'
4. Run 'conda activate NextJSFlask'

Your prompt should now be prefixed with (NextJSFlaskEnv)

## Start the API
1. Navigate to 'API' folder
2. Run flask --app hello run

Verify in the browser that you are running @ 'localhost:5000/api/hello'

## Start the UI
1. Navigate to 'UI' folder
2. Run 'npm run build'
3. Run 'npm run start'

Verify in the browser that you are running @ 'localhost:3000/hello'

