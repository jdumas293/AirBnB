# AirBnB

## Add a Spot

Adds a new spot

* Require Authentication: true
* Require proper authorization: Spot must belong to the current user
* Request
    * Method: POST
    * URL: ?
    * Body: none

* Successful Response
    * Status Code: 200
    * Headers:
        * Content-Type: application/json
    * Body:

        ```json
        {
            "message": "Successfully added",
            "statusCode": 200
        }
        ```

* Error Response: Error adding new spot
    * Status Code: 404
    * Headers:
        * Content-Type: application/json
    * Body:

        ```json
        {
            "message": "Spot couldn't be added",
            "statusCode": 404
        }
        ```

## Delete a Spot

Deletes an existing spot

* Require Authentication: true
* Require proper authorization: Spot must belong to the current user
* Request
    * Method: DELETE
    * URL: ?
    * Body: none

* Successful Response
    * Status Code: 200
    * Headers:
        * Content-Type: application/json
    * Body:

        ```json
        {
            "message": "Successfully deleted",
            "statusCode": 200
        }
        ```

* Error Response: Couldn't find a Spot with the specified id
    * Status Code: 404
    * Headers:
        * Content-Type: application/json
    * Body:

        ```json
        {
            "message": "Spot couldn't be found",
            "statusCode": 404
        }
        ```


## Create New User

## Delete Existing User
