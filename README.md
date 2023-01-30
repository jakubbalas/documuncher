# documuncher

Important: This project is primarily aimed for us to learn Rust.


## Goal

Provide a service that composes documentation from registered repos, compiles it, presents it and allows a simple search.


## How do we work on the project

Get VS Code and we will try to "group-program" together with features it provides. Some bits can be done in the free time outside of the meeting. 

## Next steps
- Decide on how to do discovery or readme files -> Register project in the tool (git url? webhook?)
- Is there Rust n Git service / library / cargo existing ? How to use Git programmatically in Rust ?
- Infra: docker-composing > docker file with services we want to use (Redis for caching) 


## Misc Notes

### Architectural mini-decisions (not yet 100% agreed)
DB: Sqlite. 
API: Hyper > 1.0 + Salvo  
Cache: Redis (also allows full text search). 
UI: Askama or Yew, find a cargo for working with markdowns.

