# hall1000
Very simple, primitive app, to just remember, what I have to remember. 

## General assumptions:
1. Project created to use as REST Api, without own client. Client can developed
in another way


## Major functionalites:

1. Users accounts
2. Free category tree 
3. Posts with pattern: title, shortBody (short content)
4. Tags - tags related with posts, to easier find



### Users accounts
. Standard functionality, too allowed create individual identifiers (based on email)

#### Basic ACL -> to which object user has an access
 - be default user should have access to objects created by him/herself

### Category tree
 - User can create own categories, which would be assign, to created posts
  (like: todos, remember, shorttags)

### Posts
 - Posts with major fields: title, short content (to 255 - like twitter ;-))

### Tags
- Tags, related with posts: many to many, one tag can be related with many posts,
posts can be related with any tags!


