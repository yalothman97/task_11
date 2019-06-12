1. Setup a virtual environment.
2. Fork the repository for [Django Task 11](https://github.com/JoinCODED/task_11) in JoinCODED’s Github and Clone it.
3. Install the packages from the requirements file.
4. Only permit users who are logged in to create `Restaurant` objects. Redirect users to the `signin` page if they are not logged in.
5. Only permit staff users to delete `Restaurant` objects. Users without access should be redirected to a page saying you have no access!
6. Only permit staff or owners of the `Restaurant` object to update. Users without access should be redirected to a page saying you have no access!
7. Only permit staff or owners of the `Restaurant` object to add/create an `Item`. Users without access should be redirected to a page saying you have no access!
8. If a user is logged in he/she should only see the `signout` option and their username in the nav-bar.
9. If a user is logged out he/she should only see the `signin` and `singup` options in the nav-bar.
10. Only logged in users can see the `Create Restaurant` option in the nav-bar.
11. Only staff users can see the **delete button** in the `restaurant_detail` page.
12. Only staff and owners of the `Restaurant` object can see the **update button** in the `restaurant_detail` page.
13. Only staff and owners of the `Restaurant` object can see the **add item button** in the `restaurant_detail` page.
14. Pass the tests
15. Push your code
