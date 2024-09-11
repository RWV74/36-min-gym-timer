# 🏋🏿 36 min gym timer

[online page](https://tobiasz-gleba.github.io/30-mingym/) - obsolete / disabled

[dowland images update MP4 tutorial](https://github.com/tobiasz-gleba/30-mingym/raw/master/docs/tutorial.mov)

[Investigate page updates](https://github.com/RWV74/36-min-gym-timer/actions)

[Install agent on the server](https://github.com/RWV74/36-min-gym-timer/settings/actions/runners/new?arch=x64&os=linux)

bash -c 'until curl http://localhost; do echo "Retrying in 5 seconds..."; sleep 5; done && firefox --kiosk http://localhost && xdotool keydown Super_L && xdotool keyup Super_L && sleep 5 && xdotool keydown Super_L && xdotool keyup Super_L;'