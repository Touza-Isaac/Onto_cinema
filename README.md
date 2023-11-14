# OntoCin_light - Cinema Ontology

## Author
- **Name:** Samdale Amaria
- **Status:** PhD Student in Computer Science
- **University:** University of Maroua

## Description
OntoCin_light is a lightweight ontology of cinema designed to model concepts and relationships related to the film industry. This ontology can be used to represent information about films, actors, genres, studios, etc.

## Content
The OntoCin_light ontology includes the following elements:

- **Main Classes:**
  - Film
  - Actor
  - Director
  - Genre
  - Studio, etc.

- **Relationships:**
  - hasActor (a film has an actor)
  - hasDirector (a film has a director)
  - BelongsToGenre (a film belongs to a genre)
  - ProducedByStudio (a film is produced by a studio), etc.

## Usage
This ontology can be used to represent cinematographic data in a structured manner. You can integrate it into cinema-related projects, extend it to meet specific needs, or use it as a starting point to develop more complex ontologies.

## Examples
```rdf
:Film1 rdf:type :Film ;
    :hasActor :Actor1, :Actor2 ;
    :hasDirector :Director1 ;
    :BelongsToGenre :Action, :Adventure ;
    :ProducedByStudio :StudioXYZ .
```
