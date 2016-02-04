# xconf.net
Private dotfile storage, and public config gallery.

# Roadmap

## Public Config Gallery

- [ ] Store dotfiles
  - [ ] Create a repo of directories [1]
  - [ ] Define template for applications [#1](https://github.com/PMaynard/xconf.net/issues/1)
- [ ] Generate Gallery Image
  - [ ] Test application with theme
  - [ ] Setup some stock windows and data
  - [ ] Capture image
- [ ] Generate webpage of dotfle and image

## Private dotfile storage

- [ ] Setup public Git server
- [ ] xconf client monitor changes of files and up/download.
	- [ ] Git commit on change
	- [ ] Wrapper for client side encryption 
	- [ ] Wrapper for rsync down/up to client

### [1] Structure

    /gallery
      /application
        /user
          /.application-rc
          /.application
            /application-theme
