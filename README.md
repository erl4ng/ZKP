                    Prover                                   Verifier
                ----------------                        ------------------
             |  Private Key x  |                    |  Public Key y = G^x |
                ----------------                        ------------------
                     |                                             |
                     |     Random number r                      |
                     |----------------------------------------->|
                     |                                             |
                     |     Compute R = G^r                      |
                     |<-----------------------------------------|
                     |                                             |
                     |     Challenge with random c              |
                     |----------------------------------------->|
                     |                                             |
                     |     Compute s = r + cx                    |
                     |<-----------------------------------------|
                     |                                             |
                     |     Verify R = G^s - y^c                 |
                     |----------------------------------------->|
                     |                                             |
                     |               Accept/Reject              |
                     |<-----------------------------------------|
