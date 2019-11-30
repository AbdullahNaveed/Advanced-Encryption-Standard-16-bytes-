

                ----------------------------------------------------------------------
                *                                                                   *
                *              Advanced Encryption Standard  (16 bytes)             *
                *                                                                   *
                ----------------------------------------------------------------------


                Encryption:

                    Function = Encrypt(message, key, encryptedMessage);

                    Requirements:
                        1.Message string (16 words)
                        2.A key string (16 words key through which will be used to encrypt and decrypt).
                        3.Another string in which cipher text will be saved


                Decryption:

                    Function = Decrypt(encryptedMessage, key, message);

                    Requirements:
                        1.Cipher Text (16 words)
                        2.Same key string used for Encryption
                        3.Another string in which normal text will be saved

