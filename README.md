
# Dynamic Allocation of Spectrum for IoT devices

This repositery consists of different models me and my team have created for our project Dynamic Allocation of Spectrum for IOT devices🖥️

This is a networks based project, the models are modeled in simulink and matlab.




## Authors

- [@Sampath844](https://github.com/Sampath844)
- [@kanapathi123](https://github.com/kanapathi123)
- [@N1sChaLLL](https://github.com/N1sChaLLL)


## Deployment

To run the models in simulink, run this script with the designated model name.

```bash
  open_system('network_model');
  set_param('network_model', 'StopTime', '20');
  simOut = sim('network_model');
  close_system('network_model', 0);
  yout = simOut.get('yout');  % Example for extracting output data
```


## Lessons Learned

1) We learnt what is a spectrum and how it is used in networks.
2) We created algorithms and models to allocate these spectrum dynamically for IoT devices.
3) We applied this knowledge to implement in one of our college IoT labs.
4) We learnt how to use simulink and matlab with other modelling softwares.

## Support

If you have any feedback, please reach out to us at 
bl.en.u4cse22201@bl.students.amrita.edu
bl.en.u4cse22241@bl.students.amrita.edu
bl.en.u4cse22261@bl.students.amrita.edu


## Worked under 
![Logo](https://www.careerguide.com/career/wp-content/uploads/2023/07/Amrita-University.png)

