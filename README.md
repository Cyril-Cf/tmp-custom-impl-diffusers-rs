# tmp-custom-impl-diffusers-rs

Doesn't work as is, it is just a custom example of the marvelous examples in :
https://github.com/LaurentMazare/diffusers-rs/

## What I changed
I added some little tweaks to an example provided (stable-diffusion), this repo is just to save my temporary version of the file main.rs. I intend to build a correct app later with proper dependencies and documentation.

## Important
Don't forget to add this to the dependencies in the cargo.toml
>chrono = "0.4"

Don't forget to add a folder /results at the root of the project


## An example of a command I would use :
> cargo run --example stable-diffusion --features clap -- --prompt "an old white lady, photography, 4k, black and white" --num-samples=4 --n-steps=150 --seed=79234987894  --negative-prompt "tiling, out of frame, extra limbs, deformed, body out of frame, bad anatomy, watermark, signature, cut off, low contrast, underexposed, overexposed, bad art, beginner, amateur, distorted face" --final-image=germaine
