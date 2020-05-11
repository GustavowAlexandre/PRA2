package com.example.agendiario;



import androidx.annotation.NonNull;
import androidx.annotation.Nullable;
import androidx.room.ColumnInfo;
import androidx.room.Entity;
import androidx.room.PrimaryKey;


@Entity(tableName = "phrases")



public class Phrases {

 
    @PrimaryKey(autoGenerate = true)
    @NonNull
    @ColumnInfo(name = "phrasesId")
    private int mId;

    @Nullable
    @ColumnInfo(name = "phrasesDescription")
    private String mDescription;

    private String mAuthor;

    public TVSeries(@Nullable String description, String author, int score, String creationDate) {
        mDescription = description;
        mAuthor = author;
        mScore = score;
        mCreationDate = creationDate;
    }

    public int getId() {
        return mId;
    }

    public void setId(int id) {
        mId = id;
    }

    public String getDescription() {
        return mDescription;
    }

    public void setDescription(String description) {
        mDescription = description;
    }

    public String getAuthor() {
        return mAuthor;
    }

    public void setAuthor(String author) {
        mAuthor = author;
    }

    public int getScore() {
        return mScore;
    }

    public void setScore(int score) {
        mScore = score;
    }

    public String getCreationDate() {
        return mCreationDate;
    }

    public void setCreationDate(String creationDate) {
        mCreationDate = creationDate;
    }

    private int mScore;
    private String mCreationDate;

}
