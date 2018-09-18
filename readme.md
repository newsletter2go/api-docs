# Newsletter2Go API Postman Collection

## Welcome 

Hi and thanks for using Newsletter2Go.

This repository is used to version our Postman collection. If you are looking for the full API documentation, please visit [https://docs.newsletter2go.com](https://docs.newsletter2go.com).


If you found a bug or would like to improve our Postman collection, please create a pull request.  
If you want to get notified when we add or change API calls, make sure to watch this repository.  
If you like what we do, leave a ⭐. Our developers will appreciate it 😉

Last but not least, you can always contact our [technical support team](mailto:support@newsletter2go.com?subject=Newsletter2Go%20API%20Postman%20Collection).

## How to use

1. Download the free [Postman app](https://www.getpostman.com/apps) or the [Chrome browser extension](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop)
1. Visit [https://docs.newsletter2go.com](https://docs.newsletter2go.com) and click the [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/ff22ffca7dd70cc6231a#?env%5BNewsletter2Go%20API%5D=W3sidmFsdWUiOiJ7e3lvdXIgTmV3c2xldHRlcjJHbyB1c2VybmFtZX19Iiwia2V5IjoidXNlcm5hbWUiLCJlbmFibGVkIjp0cnVlfSx7InZhbHVlIjoie3t5b3VyIE5ld3NsZXR0ZXIyR28gcGFzc3dvcmR9fSIsImtleSI6InBhc3N3b3JkIiwiZW5hYmxlZCI6dHJ1ZX0seyJ2YWx1ZSI6Int7eW91ciBOZXdzbGV0dGVyMkdvIGF1dGgga2V5fX0iLCJrZXkiOiJhdXRoX2tleSIsImVuYWJsZWQiOnRydWV9LHsidmFsdWUiOiJ7e3JlZnJlc2ggdG9rZW4gcmV0dXJuZWQgYnkgdGhlIE9BdXRoIGVuZHBvaW50fX0iLCJrZXkiOiJyZWZyZXNoX3Rva2VuIiwiZW5hYmxlZCI6dHJ1ZX0seyJ2YWx1ZSI6Int7YWNjZXNzIHRva2VuIHJldHVybmVkIGJ5IHRoZSBPQXV0aCBlbmRwb2ludH19Iiwia2V5IjoiYWNjZXNzX3Rva2VuIiwiZW5hYmxlZCI6dHJ1ZX0seyJ2YWx1ZSI6Int7eW91ciBiYXNlNjQgZW5jb2RlZCBOZXdzbGV0dGVyMkdvIGF1dGgga2V5fX0iLCJrZXkiOiJhdXRoX2tleV9iYXNlNjQiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImF1dGhfa2V5X3BhcnRfdXNlcm5hbWUiLCJ2YWx1ZSI6Ijx3aWxsIGJlIGZpbGxlZCBieSBQb3N0bWFuIGFmdGVyIHRoZSBPYXV0aCBjYWxsPiIsImRlc2NyaXB0aW9uIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJhdXRoX2tleV9wYXJ0X3Bhc3N3b3JkIiwidmFsdWUiOiI8d2lsbCBiZSBmaWxsZWQgYnkgUG9zdG1hbiBhZnRlciB0aGUgT2F1dGggY2FsbD4iLCJkZXNjcmlwdGlvbiI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoibGlzdF9pZCIsInZhbHVlIjoie3tsaXN0X2lkfX0iLCJkZXNjcmlwdGlvbiI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiYXR0cmlidXRlX2lkIiwidmFsdWUiOiJ7e2F0dHJpYnV0ZV9pZH19IiwiZGVzY3JpcHRpb24iOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImF0dHJpYnV0ZV9uYW1lIiwidmFsdWUiOiJ7e2F0dHJpYnV0ZV9uYW1lfX0iLCJkZXNjcmlwdGlvbiI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiY29tcGFueV9pZCIsInZhbHVlIjoie3tjb21wYW55X2lkfX0iLCJkZXNjcmlwdGlvbiI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoidXNlcl9pZCIsInZhbHVlIjoie3t1c2VyX2lkfX0iLCJkZXNjcmlwdGlvbiI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoicmVjaXBpZW50X2lkIiwidmFsdWUiOiJ7e3JlY2lwaWVudF9pZH19IiwiZGVzY3JpcHRpb24iOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6Imdyb3VwX2lkIiwidmFsdWUiOiJ7e2dyb3VwX2lkfX0iLCJkZXNjcmlwdGlvbiI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiZmlsZV9pZCIsInZhbHVlIjoie3tmaWxlX2lkfX0iLCJkZXNjcmlwdGlvbiI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiaW1wb3J0X2lkIiwidmFsdWUiOiJ7e2ltcG9ydF9pZH19IiwiZGVzY3JpcHRpb24iOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6Im5ld3NsZXR0ZXJfaWQiLCJ2YWx1ZSI6Int7bmV3c2xldHRlcl9pZH19IiwiZGVzY3JpcHRpb24iOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImZvcm1faWQiLCJ2YWx1ZSI6Int7Zm9ybV9pZH19IiwiZGVzY3JpcHRpb24iOiIiLCJlbmFibGVkIjp0cnVlfV0=) button _or_   
1. Download the Postman JSON file from the folder `Postman Collections` in this repository, open Postman and import the file.  
1. Make sure to select the `Newsletter2Go API` environment on the top right  
1. Add your user credentials to the environment variables
1. Run the first `Authentication` request. (Your `access token` will be automatically stored within the environment variables)
1. Make any other subsequent call that you like 
