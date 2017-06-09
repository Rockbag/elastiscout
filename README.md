# elastiscout
A quick &amp; dirty tool used to acquire the IP address of every EC2 node within an Elastic Beanstalk application environment
I mean really dirty. 

## Setup

```
git clone git@github.com:Rockbag/elastiscout.git
cd elastiscout
cp elastiscout /usr/local/bin
```

## Usage
```
cd your-elastic-beanstalk-app-folder
elastiscout environmentName
```

### If you have cssh set up, you can do
`cssh $(elastiscout environmentName)`
