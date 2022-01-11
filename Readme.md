# GCP Group

Pass project ID to see your group list of project!!!
Don't forget pass GCP_KEY:

    export GCP_TOKEN=`gcloud auth print-access-token`

To run script:

    go run main.go test5-123456

if project don't have groups you see an empty array.
return like this:

    statusCode: 200
    {}
