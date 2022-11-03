# ThreatMapper-Workshop


# Demo1 

## Deploy ThreatMapper Console using Docker Compose on Linux VM using AWS EC2 

- Create Ubuntu Instance on AWS EC2 









```
[+] Running 132/133al-router Pulled                                                                                                    5.1s
 ⠧ deepfence-ui Pulling                                                                                                               55.8s
   ⠿ ee30d1e46960 Pull complete                                                                                                       18.1s
   ⠿ cbdf55152882 Pull complete                                                                                                       20.7s
   ⠿ 02145a3d08dc Pull complete                                                                                                       24.4s
   ⠿ 3b43024e0402 Pull complete                                                                                                       25.5s
   ⠿ 000a421a9381 Pull complete                                                                                                       25.8s
   ⠿ 273e2d14a316 Pull complete                                                                                                       26.1s
   ⠿ 35f2174af386 Pull complete                                                                                                       52.7s
   ⠿ 3bf6d37d02af Pull complete                                                                                                       53.2s
   ⠿ 2ebf2edf21e9 Pull complete                                                                                                       53.7s
   ⠿ 70ecf58c4679 Pull complete                                                                                                       54.1s
 ⠿ deepfence-package-scanner Pulled                                                                                                    8.8s
   ⠿ 51dd59142225 Pull complete                                                                                                        4.0s
   ⠿ afd427f95343 Pull complete                                                                                                        5.2s
   ⠿ ad4b784c8601 Pull complete                                                                                                        7.5s
 ⠿ deepfence-backend Pulled                                                                                                           48.2s
 ⠿ deepfence-console-agent Pulled                                                                                                     46.4s
   ⠿ e0c9ebf1f052 Pull complete                                                                                                       25.5s
   ⠿ 9341ad80650d Pull complete                                                                                                       26.0s
   ⠿ b6a94e577185 Pull complete                                                                                                       26.9s
   ⠿ f2f4f6c497c7 Pull complete                                                                                                       27.4s
   ⠿ 83dc6dff4d1f Pull complete                                                                                                       27.8s
   ⠿ 2c66b377cc17 Pull complete                                                                                                       28.1s
   ⠿ ae95bb3e76fc Pull complete                                                                                                       29.9s
   ⠿ 58edf371ef84 Pull complete                                                                                                       30.5s
   ⠿ b5b91601778a Pull complete                                                                                                       30.9s
   ⠿ e7ca0b813b35 Pull complete                                                                                                       31.4s
   ⠿ bac5f99ed5ff Pull complete                                                                                                       32.2s
   ⠿ 0b03b6c6e703 Pull complete                                                                                                       32.7s
   ⠿ 00ef62c6beae Pull complete                                                                                                       33.1s
   ⠿ 2317941b432c Pull complete                                                                                                       33.4s
   ⠿ c78d4ef87429 Pull complete                                                                                                       33.8s
   ⠿ 52d6b999791e Pull complete                                                                                                       37.0s
   ⠿ 3c66ae264813 Pull complete                                                                                                       40.4s
   ⠿ fa91d8140bb4 Pull complete                                                                                                       44.0s
   ⠿ 415ec3af8b5c Pull complete                                                                                                       45.0s
 ⠿ deepfence-diagnosis Pulled                                                                                                          9.3s
   ⠿ d8089fb41a4e Pull complete                                                                                                        7.2s
   ⠿ 761247dc597b Pull complete                                                                                                        7.9s
 ⠿ deepfence-vulnerability-mapper Pulled                                                                                               9.0s
   ⠿ 9621f1afde84 Pull complete                                                                                                        4.8s
   ⠿ d2f87f45af97 Pull complete                                                                                                        5.8s
   ⠿ 0df38fc1dcc4 Pull complete                                                                                                        5.8s
   ⠿ 5ce3bac9b38d Pull complete                                                                                                        6.0s
   ⠿ b8a17e0751b8 Pull complete                                                                                                        7.7s
 ⠿ deepfence-redis Pulled                                                                                                             20.4s
   ⠿ 192e03523482 Pull complete                                                                                                       14.1s
   ⠿ 7151bccd2756 Pull complete                                                                                                       14.9s
   ⠿ e599fac432b2 Pull complete                                                                                                       16.0s
   ⠿ 720d86c10923 Pull complete                                                                                                       16.5s
   ⠿ 40911e48517b Pull complete                                                                                                       16.9s
   ⠿ 115eb662e680 Pull complete                                                                                                       17.3s
   ⠿ 31b9b283aa20 Pull complete                                                                                                       17.9s
   ⠿ b748b52207f7 Pull complete                                                                                                       18.3s
   ⠿ 5b0f449535b8 Pull complete                                                                                                       18.9s
 ⠿ deepfence-api Pulled                                                                                                               48.3s
   ⠿ 31b3f1ad4ce1 Pull complete                                                                                                        1.8s
   ⠿ f335cc1597f2 Pull complete                                                                                                        2.0s
   ⠿ 0375df124bb5 Pull complete                                                                                                        2.6s
   ⠿ 90a356bcda5b Pull complete                                                                                                        2.7s
   ⠿ c82e0170c13b Pull complete                                                                                                        2.9s
   ⠿ 38dc58c5f029 Pull complete                                                                                                        3.0s
   ⠿ 0189a7ca7a09 Pull complete                                                                                                       40.8s
   ⠿ 8d069dc99fe4 Pull complete                                                                                                       45.2s
   ⠿ 50e62824984f Pull complete                                                                                                       45.6s
   ⠿ c12613b81b5c Pull complete                                                                                                       45.8s
   ⠿ c8901960f9b5 Pull complete                                                                                                       45.9s
   ⠿ a5981c5eb3db Pull complete                                                                                                       46.3s
   ⠿ 860d4f2e0b1a Pull complete                                                                                                       46.8s
   ⠿ 8a3f7b35b548 Pull complete                                                                                                       47.0s
   ⠿ 37c02a7c1188 Pull complete                                                                                                       47.4s
 ⠿ deepfence-celery Pulled                                                                                                            48.2s
 ⠿ deepfence-postgres Pulled                                                                                                          28.2s
   ⠿ 7902437d3a12 Pull complete                                                                                                       10.9s
   ⠿ 709e2267bc98 Pull complete                                                                                                       11.5s
   ⠿ 10c5a0a9c34e Pull complete                                                                                                       21.4s
   ⠿ b46af7f38693 Pull complete                                                                                                       22.4s
   ⠿ 65aa0c237f80 Pull complete                                                                                                       23.3s
   ⠿ f6493ce74812 Pull complete                                                                                                       24.0s
   ⠿ eaac3b44f9d0 Pull complete                                                                                                       24.5s
   ⠿ 3b6db84bcdcc Pull complete                                                                                                       25.1s
   ⠿ 120ba5542ffd Pull complete                                                                                                       25.5s
   ⠿ 9fd0e93acee4 Pull complete                                                                                                       25.8s
   ⠿ 257465d6d91b Pull complete                                                                                                       26.1s
   ⠿ 568fad078a9c Pull complete                                                                                                       26.5s
 ⠿ deepfence-init-container Pulled                                                                                                    14.8s
   ⠿ 2ad0d7925a78 Pull complete                                                                                                       12.6s
   ⠿ 3e00d8e06113 Pull complete                                                                                                       13.2s
 ⠿ deepfence-es Pulled                                                                                                                41.1s
   ⠿ 4e9f2cdf4387 Pull complete                                                                                                       15.3s
   ⠿ 2e70516637d4 Pull complete                                                                                                       37.1s
   ⠿ ba468cc9ce22 Pull complete                                                                                                       37.6s
   ⠿ a2c864bf08ba Pull complete                                                                                                       38.1s
   ⠿ 7869dc55514f Pull complete                                                                                                       38.8s
   ⠿ 6320c0eaee7c Pull complete                                                                                                       39.5s
[+] Running 133/133al-router Pulled                                                                                                    5.1s
 ⠿ deepfence-ui Pulled                                                                                                                55.9s
   ⠿ ee30d1e46960 Pull complete                                                                                                       18.1s
   ⠿ cbdf55152882 Pull complete                                                                                                       20.7s
   ⠿ 02145a3d08dc Pull complete                                                                                                       24.4s
   ⠿ 3b43024e0402 Pull complete                                                                                                       25.5s
   ⠿ 000a421a9381 Pull complete                                                                                                       25.8s
   ⠿ 273e2d14a316 Pull complete                                                                                                       26.1s
   ⠿ 35f2174af386 Pull complete                                                                                                       52.7s
   ⠿ 3bf6d37d02af Pull complete                                                                                                       53.2s
   ⠿ 2ebf2edf21e9 Pull complete                                                                                                       53.7s
   ⠿ 70ecf58c4679 Pull complete                                                                                                       54.1s
 ⠿ deepfence-package-scanner Pulled                                                                                                    8.8s
   ⠿ 51dd59142225 Pull complete                                                                                                        4.0s
   ⠿ afd427f95343 Pull complete                                                                                                        5.2s
   ⠿ ad4b784c8601 Pull complete                                                                                                        7.5s
 ⠿ deepfence-backend Pulled                                                                                                           48.2s
 ⠿ deepfence-console-agent Pulled                                                                                                     46.4s
   ⠿ e0c9ebf1f052 Pull complete                                                                                                       25.5s
   ⠿ 9341ad80650d Pull complete                                                                                                       26.0s
   ⠿ b6a94e577185 Pull complete                                                                                                       26.9s
   ⠿ f2f4f6c497c7 Pull complete                                                                                                       27.4s
   ⠿ 83dc6dff4d1f Pull complete                                                                                                       27.8s
   ⠿ 2c66b377cc17 Pull complete                                                                                                       28.1s
   ⠿ ae95bb3e76fc Pull complete                                                                                                       29.9s
   ⠿ 58edf371ef84 Pull complete                                                                                                       30.5s
   ⠿ b5b91601778a Pull complete                                                                                                       30.9s
   ⠿ e7ca0b813b35 Pull complete                                                                                                       31.4s
   ⠿ bac5f99ed5ff Pull complete                                                                                                       32.2s
   ⠿ 0b03b6c6e703 Pull complete                                                                                                       32.7s
   ⠿ 00ef62c6beae Pull complete                                                                                                       33.1s
   ⠿ 2317941b432c Pull complete                                                                                                       33.4s
   ⠿ c78d4ef87429 Pull complete                                                                                                       33.8s
   ⠿ 52d6b999791e Pull complete                                                                                                       37.0s
   ⠿ 3c66ae264813 Pull complete                                                                                                       40.4s
   ⠿ fa91d8140bb4 Pull complete                                                                                                       44.0s
   ⠿ 415ec3af8b5c Pull complete                                                                                                       45.0s
 ⠿ deepfence-diagnosis Pulled                                                                                                          9.3s
   ⠿ d8089fb41a4e Pull complete                                                                                                        7.2s
   ⠿ 761247dc597b Pull complete                                                                                                        7.9s
 ⠿ deepfence-vulnerability-mapper Pulled                                                                                               9.0s
   ⠿ 9621f1afde84 Pull complete                                                                                                        4.8s
   ⠿ d2f87f45af97 Pull complete                                                                                                        5.8s
   ⠿ 0df38fc1dcc4 Pull complete                                                                                                        5.8s
   ⠿ 5ce3bac9b38d Pull complete                                                                                                        6.0s
   ⠿ b8a17e0751b8 Pull complete                                                                                                        7.7s
 ⠿ deepfence-redis Pulled                                                                                                             20.4s
   ⠿ 192e03523482 Pull complete                                                                                                       14.1s
   ⠿ 7151bccd2756 Pull complete                                                                                                       14.9s
   ⠿ e599fac432b2 Pull complete                                                                                                       16.0s
   ⠿ 720d86c10923 Pull complete                                                                                                       16.5s
   ⠿ 40911e48517b Pull complete                                                                                                       16.9s
   ⠿ 115eb662e680 Pull complete                                                                                                       17.3s
   ⠿ 31b9b283aa20 Pull complete                                                                                                       17.9s
   ⠿ b748b52207f7 Pull complete                                                                                                       18.3s
   ⠿ 5b0f449535b8 Pull complete                                                                                                       18.9s
 ⠿ deepfence-api Pulled                                                                                                               48.3s
   ⠿ 31b3f1ad4ce1 Pull complete                                                                                                        1.8s
   ⠿ f335cc1597f2 Pull complete                                                                                                        2.0s
   ⠿ 0375df124bb5 Pull complete                                                                                                        2.6s
   ⠿ 90a356bcda5b Pull complete                                                                                                        2.7s
   ⠿ c82e0170c13b Pull complete                                                                                                        2.9s
   ⠿ 38dc58c5f029 Pull complete                                                                                                        3.0s
   ⠿ 0189a7ca7a09 Pull complete                                                                                                       40.8s
   ⠿ 8d069dc99fe4 Pull complete                                                                                                       45.2s
   ⠿ 50e62824984f Pull complete                                                                                                       45.6s
   ⠿ c12613b81b5c Pull complete                                                                                                       45.8s
   ⠿ c8901960f9b5 Pull complete                                                                                                       45.9s
   ⠿ a5981c5eb3db Pull complete                                                                                                       46.3s
   ⠿ 860d4f2e0b1a Pull complete                                                                                                       46.8s
   ⠿ 8a3f7b35b548 Pull complete                                                                                                       47.0s
   ⠿ 37c02a7c1188 Pull complete                                                                                                       47.4s
 ⠿ deepfence-celery Pulled                                                                                                            48.2s
 ⠿ deepfence-postgres Pulled                                                                                                          28.2s
   ⠿ 7902437d3a12 Pull complete                                                                                                       10.9s
   ⠿ 709e2267bc98 Pull complete                                                                                                       11.5s
   ⠿ 10c5a0a9c34e Pull complete                                                                                                       21.4s
   ⠿ b46af7f38693 Pull complete                                                                                                       22.4s
   ⠿ 65aa0c237f80 Pull complete                                                                                                       23.3s
   ⠿ f6493ce74812 Pull complete                                                                                                       24.0s
   ⠿ eaac3b44f9d0 Pull complete                                                                                                       24.5s
   ⠿ 3b6db84bcdcc Pull complete                                                                                                       25.1s
   ⠿ 120ba5542ffd Pull complete                                                                                                       25.5s
   ⠿ 9fd0e93acee4 Pull complete                                                                                                       25.8s
   ⠿ 257465d6d91b Pull complete                                                                                                       26.1s
   ⠿ 568fad078a9c Pull complete                                                                                                       26.5s
 ⠿ deepfence-init-container Pulled                                                                                                    14.8s
   ⠿ 2ad0d7925a78 Pull complete                                                                                                       12.6s
   ⠿ 3e00d8e06113 Pull complete                                                                                                       13.2s
 ⠿ deepfence-es Pulled                                                                                                                41.1s
   ⠿ 4e9f2cdf4387 Pull complete                                                                                                       15.3s
   ⠿ 2e70516637d4 Pull complete                                                                                                       37.1s
   ⠿ ba468cc9ce22 Pull complete                                                                                                       37.6s
   ⠿ a2c864bf08ba Pull complete                                                                                                       38.1s
   ⠿ 7869dc55514f Pull complete                                                                                                       38.8s
   ⠿ 6320c0eaee7c Pull complete                                                                                                       39.5s
 ⠿ deepfence-internal-router Pulled                                                                                                    5.1s
 ⠿ deepfence-secret-scanner Pulled                                                                                                    43.2s
   ⠿ c963e9db8328 Pull complete                                                                                                       34.6s
   ⠿ 7f20bc208900 Pull complete                                                                                                       35.0s
   ⠿ a11f9e68c7c1 Pull complete                                                                                                       36.3s
   ⠿ bac7f7e29d55 Pull complete                                                                                                       36.5s
   ⠿ a34450f81e53 Pull complete                                                                                                       37.2s
   ⠿ 8dc83348f20e Pull complete                                                                                                       41.0s
   ⠿ 1789eac203f6 Pull complete                                                                                                       41.6s
 ⠿ deepfence-fetcher Pulled                                                                                                           44.4s
   ⠿ 59bf1c3509f3 Pull complete                                                                                                       22.1s
   ⠿ 7f019d2ddd3b Pull complete                                                                                                       23.2s
   ⠿ d365c5dd6d5a Pull complete                                                                                                       23.7s
   ⠿ 86b2e2904ff3 Pull complete                                                                                                       24.2s
   ⠿ 9e8d01c5b686 Pull complete                                                                                                       42.5s
 ⠿ deepfence-router Pulled                                                                                                             5.1s
   ⠿ df9b9388f04a Pull complete                                                                                                        1.8s
   ⠿ 7c1ae225ee09 Pull complete                                                                                                        1.9s
   ⠿ d67475b58d2b Pull complete                                                                                                        2.5s
   ⠿ 403f08e781eb Pull complete                                                                                                        2.6s
   ⠿ 452f212a53d1 Pull complete                                                                                                        2.8s
   ⠿ 437cebde658b Pull complete                                                                                                        2.8s
   ⠿ 7c9ad45672b2 Pull complete                                                                                                        2.9s
   ⠿ 7d72372a1383 Pull complete                                                                                                        3.1s
   ⠿ d6bb5a9a1f12 Pull complete                                                                                                        3.2s
   ⠿ 7cf149b1a854 Pull complete                                                                                                        3.3s
   ⠿ b6e2429d9e38 Pull complete                                                                                                        3.3s
   ⠿ 92dcd490ec00 Pull complete                                                                                                        3.4s
   ⠿ 617b7a99eac3 Pull complete                                                                                                        3.5s
   ⠿ 259e00ee3450 Pull complete                                                                                                        3.6s
   ⠿ 83bec234123b Pull complete                                                                                                        3.7s
   ⠿ 928a4d3b5efe Pull complete                                                                                                        3.8s
 ⠿ deepfence-topology Pulled                                                                                                          34.0s
   ⠿ a0d0a0d46f8b Pull complete                                                                                                       16.0s
   ⠿ 127cfa2b873d Pull complete                                                                                                       16.6s
   ⠿ 15a88de45267 Pull complete                                                                                                       30.3s
   ⠿ 35233bb75987 Pull complete                                                                                                       32.0s
   ⠿ 8133cfb2a953 Pull complete                                                                                                       32.4s
[+] Running 19/19
 ⠿ Network ubuntu_deepfence_net              Created                                                                                   0.3s
 ⠿ Volume "ubuntu_deepfence_data"            Created                                                                                   0.0s
 ⠿ Container deepfence-postgres              Started                                                                                  16.5s
 ⠿ Container deepfence-secret-scanner        Started                                                                                  18.4s
 ⠿ Container deepfence-vulnerability-mapper  Started                                                                                  17.3s
 ⠿ Container deepfence-diagnosis             Started                                                                                  17.5s
 ⠿ Container deepfence-package-scanner       Started                                                                                  17.7s
 ⠿ Container deepfence-console-agent         Started                                                                                  16.0s
 ⠿ Container deepfence-es-master             Started                                                                                  17.1s
 ⠿ Container df-init-container               Started                                                                                  16.0s
 ⠿ Container deepfence-topology              Started                                                                                  17.3s
 ⠿ Container deepfence-router                Started                                                                                  18.4s
 ⠿ Container deepfence-internal-router       Started                                                                                  17.5s
 ⠿ Container deepfence-redis                 Started                                                                                   2.3s
 ⠿ Container deepfence-ui                    Started                                                                                   2.8s
 ⠿ Container deepfence-fetcher               Started                                                                                   2.4s
 ⠿ Container deepfence-celery                Started                                                                                   3.5s
 ⠿ Container deepfence-api                   Started                                                                                   3.4s
 ⠿ Container deepfence-backend               Started                                                                                   3.1s
 ```
