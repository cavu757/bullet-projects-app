# Flatiron React Redux Portfolio Project - Bullet Projects Journal

The Bullet Projects Journal is based on the original bullet journal and a basic clone of the bullet journal app but applies it to project management.  Visit https://bulletjournal.com/pages/learn for more information.  The home page shows you your upcoming events and contains links to create a new project or to view your current projects.

## Installation

Fork database from https://github.com/cavu757/bullet-projects-app.  This will contain the Rails backend and the React-Redux frontend.  The repository is linked to the repositories for the frontend and backend but below are the links for each just in case.

Frontend: https://github.com/cavu757/bullet-projects-frontend

Backend: https://github.com/cavu757/bullet-projects-backend

Once you have forked both frontend and backend, first `cd` into the backend directory (`bullet-projects-backend`), `bundle install` to install all gems required, and `rake db:migrate` to initialize database.  Run API backend by entering `rails s`.  If you do not have anything else running, your backend should start up on http://localhost:3000/

Open a new terminal window, `cd` into the frontend directory (`bullet-projects-frontend`) and `npm install` to install all required modules.  Run React-Redux frontend by entering `npm start`.

There is a seed file but it is not required to run the application.  Go ahead and start creating some projects and adding bullets (which can be events, tasks and/or notes).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/cavu757/bullet-projects-app. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The app is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Bullet Projects Journal project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/cavu757/bullet-projects-app/blob/master/CODE_OF_CONDUCT.md).
