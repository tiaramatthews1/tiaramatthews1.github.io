---
layout: post
title:      "Object Relationships"
date:       2019-09-11 01:39:23 +0000
permalink:  object_relationships
---


Some key concepts in object Relationships I have come across were:

The "Belongs To" Rlationship

Ex: 

class Artist
  attr_accessor :name, :genre
 
  def initialize(name, genre) 
    @name = name
    @genre = genre
  end
 
end
 
drake = Artist.new("Drake", "rap")
hotline_bling = Song.new("Hotline Bling")
 
hotline_bling.artist = drake

The "has-many" Relationship

Ex: 

class Song
  attr_accessor :artist, :name, :genre
 
  @@all = []
 
  def initialize(name, genre)
    @name = name
    @genre = genre
    save
  end
 
  def save
    @@all << self
  end
 
  def self.all
    @@all
  end
end


