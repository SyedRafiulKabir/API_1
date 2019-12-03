
DOCUMENTATION of my API



my json format is

{Title:String,Content:String} example {"title":"First commit","content":"Hi there"}

1)GET https://api-2175.herokuapp.com/notes to see all content of saved app

2)GET https://api-2175s.herokuapp.com/notes/noteId to the content of the ID example{
to see
[
    {
        "_id": "5de6ad63fecee64068f8de51",
        "title": "First commit",
        "content": "Hi there",
        "createdAt": "2019-12-03T18:45:55.360Z",
        "updatedAt": "2019-12-03T18:45:55.360Z",
        "__v": 0
    }
]
this content
we have to call GET https://api-2175.herokuapp.com/notes/5de6ad63fecee64068f8de51

}

3)POST https://api-2175.herokuapp.com/notes then give a like my json format content

4)PUT https://api-2175.herokuapp.com/notes and give a json format content

5)DELETE https://api-2175.herokuapp.com/notes/noteId to delete the id related content
