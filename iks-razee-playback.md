1. `cd /Users/alewitt2/Documents/armada/razee-io/watch-keeper && . ./dev-envvars.sh`
1. open source planned for a year, come together last 6 months, replacement for cluster-updater/razeedash
1. Creating your own RazeeDash [steps](https://github.com/razee-io/Razee#step-1-install-razee)
    - shoutout to Nadine and Art
1. Sample running RazeeDash: https://app.razee.io
    - Feel free to join our demo org [github.com/razee-demo](https://github.com/razee-demo) and check it out
1. Add watch-keeper and kapitan to a new cluster https://app.razee.io/iks-playback-demo/org
1. `kubectl get crd`
1. https://github.com/alewitt2/samples/releases
    - `kubectl apply -f "https://github.com/alewitt2/samples/releases/download/0.0.1/demo-remoteresource.yaml"`
1. `kubectl get -n razee rr iks-playback-demo-rr`
1. `kubectl get -n razee cm iks-playback-demo-cm`
1. check out our other custom resources at [github.com/razee-io](https://github.com/razee-io?q=kapitan)
