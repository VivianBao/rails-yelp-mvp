# README

# 🥂 Yelpy

A practice web app that helps you find and rate your favorite restaurants!

<!-- _DROP SCREENSHOT HERE_
<br>
App home: https://WHATEVER.herokuapp.com -->


## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 6](https://guides.rubyonrails.org/) - Backend / Front-end
- [SCSS] - Front-end
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database


## Acknowledgements
Built with the help of Le Wagon Tokyo Team of Full Stack Developer course.

## Team Members
- [Vivian Bow](https://github.com/VivianBao?tab=repositories)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
