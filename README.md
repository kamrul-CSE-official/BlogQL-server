# BLOG APP

## Requirements
- User can post & published blog content
- User can see post
- Authentaction system
- User can see there own profile

## Table

-Post
    -id
    -title
    -content
    -authorId
    -createdAt
    -updatedAt
    -published

-User
    -id
    -name
    -email
    -password
    -createdAt
    -updatedAt
    -profileId

-Profile
    -id
    -bio
    -createdAt
    -updatedAt
    -userId

## Technology Stack
- GQL
- typeScript
- postgresQL
- prisma