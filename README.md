# RAC Restaurant

# 1 Create repositories
- git@github.com:rafacancian/rac-restaurant.git 
- git@github.com:rafacancian/rac-restaurant-frontend.git
- git@github.com:rafacancian/rac-restaurant-backend.git

# 2 Link projetcs
- git remote add frontend git@github.com:rafacancian/rac-restaurant-frontend.git
- git remote add backend git@github.com:rafacancian/rac-restaurant-backend.git
> set url (optional)
> - git remote set-url frontend git@github.com:rafacancian/rac-restaurant-frontend.git
> - git remote set-url backend git@github.com:rafacancian/rac-restaurant-backend.git

# 3 Add repositories to mainly project
- git subtree add --prefix=rac-restaurant-frontend/ frontend main 
- git subtree add --prefix=rac-restaurant-backend/ backend main
