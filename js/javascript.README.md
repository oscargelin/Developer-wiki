The Fetch API accesses resources across the network. You can make HTTP requests (using GET, POST and other methods), download, and upload files.

To start a request, call the special function fetch():

fetch() starts a request and returns a promise. When the request completes, the promise is resolved with the Response object. If the request fails due to some network problems, the promise is rejected.

async/await syntax fits great with fetch() because it simplifies the work with promises with syntactic sugar.

async makes a function return a Promise

await makes a function wait for a Promise
