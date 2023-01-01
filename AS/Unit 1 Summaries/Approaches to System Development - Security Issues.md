# Approaches to System Development - Security Issues

## Terms:
* [Backups](#Backups)
* [Data Archiving](#Data-Archiving)

# Backups
The backup process involves the creations of redundant copies of data for use in the event of lost data due to an unforseen critical system failure. In the event of such a failure the redundant data may be used to replace any lost data.

## Comparison Of Backup Methods

| Method              |                                Advantages                                 |                                Disadvantages                                |
|---------------------|:-------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| Full Backup         | Everything backed up at once.<br/> Quick restoration, files are complete. | Slower and uses more space due to redundancy.<br/> Everything in one place. |
| Differential Backup | Faster restores than Incremental.<br/> Smaller and faster than a full backup.<br/> | Larger than an incremental backup. |
| Incremental Backup  | Faster backups and less space used as only changed files are backed up.   | Longer recovery times.<br/> All previous incremental backups required.      |

# Data Archiving

Data archiving is the storage of information for a long period of time.

Archives consist of information not of immediate use to the organisation, however the information may be relevant later for future reference, or to comply with legislation or auditing purposes.

Data stored in an archive is typically compressed so as to occupy less space, and may be stored on lower cost mediums of storage such as optical media or magnetic media. Data archives must also be easily accessible to the end user and as such may be indexed to make the location and retrieval of items easier.