# State Variable Filter

The state variable filter is a second order (12dB/oct) filter with low-, high- and band-pass outputs and adjustable resonance. This is a classic filter design that appears in a number of synths, including the Oberheim SEM. 

* Module size: 8HP (40mm)
* Power: 15mA (+12V); 15mA (-12V)

!!! repository "State Variable Filter"

    The project files, including schematic and layout, are available on [github](https://github.com/xdylanm/state-variable-filter)

## Features

* AC-coupled line input (audio) with adjustable attenuation.
* Multiple control options for the filter cutoff frequency are summed:
    * V/oct range from 0-9V corresponding to a filter cutoff ranging from <20Hz to approximately 16kHz.
    * Two CV inputs with adjustable attenuation.
    * Cutoff frequency offset adjustment with a potentiometer.
* Low-, high-, and bandpass and notch (bandstop) filter outputs (note: the band-pass output is not normalized to the resonance gain, so its amplitude will vary with the resonance control). 

Following the [notes](https://www.eddybergman.com/2024/04/THVCF1statevariablefilter.html) from Eddy Bergman, I've opted to drop the fine-adjust for the cutoff frequency and replace it with a second CV input. 

## Documentation

[Design](theory.md)

[Assembly Guide](assembly.md)

[Schematic](assets/svf-1.pdf)

## References

1. Hal Chamberlain, *Musical Applications of Microprocessors*, 2nd Ed., Hayden Books, 1985
2. Thomas Henry, "VCF-1", [birthofasynth.com](https://www.birthofasynth.com/Thomas_Henry/Pages/VCF-1.html)
3. Eddy Bergman, "VCF-1 State Variable Filter by Thomas Henry" [eddybergman.com](https://www.eddybergman.com/2024/04/THVCF1statevariablefilter.html)
4. Ray Wilson, "State Variable VCF 12dB/Octave with VC Resonance" [MFOS](https://musicfromouterspace.com/analogsynth_new/STATEVARVCFFEB2006/STATEVARVCFFEB2006.html)
5. Kevin Lightner, "docs/Oberheim/Oberheim_SEM1A" [synthfool](https://www.synthfool.com/docs/Oberheim/Oberheim_SEM1A/)
