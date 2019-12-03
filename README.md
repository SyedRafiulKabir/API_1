
DOCUMENTATION of my API



my json format is

{Title:String,Content:String} example {"title":"First commit","content":"Hi there"}

1)GET https://esnotes.herokuapp.com/notes to see all content of saved app

2)GET https://esnotes.herokuapp.com/notes/noteId to the content of the ID example{
to see
{
    "_id": "5dde14f7d29ef72508eeeb57",
    "title": "Second",
    "content": "Hi there",
    "createdAt": "2019-11-27T06:17:27.811Z",
    "updatedAt": "2019-11-27T06:17:27.811Z",
    "__v": 0
}
this content
we have to call GET https://esnotes.herokuapp.com/notes/5dde14f7d29ef72508eeeb57

}

3)POST https://esnotes.herokuapp.com/notes then give a like my json format content

4)PUT https://esnotes.herokuapp.com/notes and give a json format content

5)DELETE https://esnotes.herokuapp.com/notes/noteId to delete the id related content
