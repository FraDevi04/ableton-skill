# Chapter 40: Drums to Pitches and Vice Versa

## Core Idea
MIDI notes are data independent of sound. Copy drum patterns to pitched instruments (transpose up, constrain to scale). Copy melodic patterns to drums (re-map to kit). Extract pitch/rhythm from audio using wrong algorithms.

## Frameworks Introduced
- **MIDI independence**: MIDI notes are data independent of sound. A MIDI note is just a number — it can trigger any sound.
- **Drums to pitches**: Copy a drum pattern to a pitched instrument (transpose up, constrain to scale). The rhythmic pattern becomes a melodic pattern.
- **Pitches to drums**: Copy a melodic pattern to a drum kit (re-map notes to appropriate kit elements). The melody becomes a drum pattern.
- **Wrong algorithm extraction**: Use pitch detection on rhythmic audio (or rhythm detection on pitched audio) — the "wrong" algorithm can reveal new ideas.

## Key Concepts
- **Data abstraction**: MIDI data exists independently of the sound it triggers
- **Cross-domain transfer**: Moving musical ideas between rhythmic and pitched domains
- **Transposition + scale constraint**: When moving drums to pitches, transpose and constrain to a scale
- **Re-mapping**: When moving pitches to drums, map notes to appropriate kit elements

## Mental Models
- Use cross-domain transfer when you need ideas in a different musical domain
- Think of MIDI as a universal language — the same data can be any sound
- The "wrong" algorithm can produce creative results

## Anti-patterns
- **Ignoring scale constraints**: Moving drums to pitches without scale constraint creates atonal results
- **Wrong re-mapping**: Mapping melodic notes to inappropriate drum sounds
- **Forcing the transfer**: Not every drum pattern works as a melody, and vice versa

## Key Takeaways
1. MIDI notes are data independent of sound — a number that can trigger any sound
2. Copy drum patterns to pitched instruments (transpose up, constrain to scale)
3. Copy melodic patterns to drum kits (re-map notes to kit elements)
4. Use "wrong" algorithms for creative extraction — pitch detection on rhythmic audio
5. This reveals hidden relationships between rhythm and melody

## Connects To
- **ch39**: Bass Lines and Kick Drums — kick drums have pitch too
- **ch41**: Tuning Everything — electronic drums have definite pitches
- **ch43**: Sampling the Old-Fashioned Way — sound independence from data
- **ch33**: Misusing Rhythmic Tools — using the wrong algorithm for extraction
