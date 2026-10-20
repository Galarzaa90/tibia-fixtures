# Fixture catalogue

HTML pages and extracts grouped by category. Each entry describes the case a fixture covers. Historical alternatives appear alongside the corresponding fixtures, with the regression cases they preserve.

## Other

|                  File                  | Extracted On |                                    Description                                     |
| -------------------------------------- | ------------ | ---------------------------------------------------------------------------------- |
| [aboutSection.html](aboutSection.html) |              | The 'About Tibia' section on Tibia.com, used to provide invalid content for tests. |

## Auctions

|                                              File                                              | Extracted On |                                                                             Description                                                                             |
| ---------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [auctionFinished.html](auction/auctionFinished.html)                                           |              | The content of a finished auction.                                                                                                                                  |
| [auctionFinishedLegacyLayout.html](auction/auctionFinishedLegacyLayout.html)                   |              | A finished auction in the earlier layout, without Fragment Progress or Proficiencies sections. Retained to test the earlier layout and transfer/achievement values. |
| [auctionNotFound.html](auction/auctionNotFound.html)                                           |              | The content of an auction that doesn't exist.                                                                                                                       |
| [auctionWithFragmentProgress.html](auction/auctionWithFragmentProgress.html)                   |              | An auction displaying fragment progress.                                                                                                                            |
| [auctionWithUpgradedItems.html](auction/auctionWithUpgradedItems.html)                         |              | An auction with upgraded items.                                                                                                                                     |
| [auctionWithUpgradedItemsLegacyLayout.html](auction/auctionWithUpgradedItemsLegacyLayout.html) |              | An auction with upgraded items in the earlier layout, showing “My Bid Limit” rather than “finished”. Retained to test the earlier layout and auction status.        |

## Boostable bosses

|                                 File                                 | Extracted On |                                                       Description                                                        |
| -------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------ |
| [bossList.html](boostableBosses/bossList.html)                       |              | The list of bosses.                                                                                                      |
| [bossListLegacyTable.html](boostableBosses/bossListLegacyTable.html) |              | The boss list using the earlier Table1 structure. Retained to test parsing before the Table5/TableContent layout change. |

## Characters

|                                         File                                         | Extracted On |                                                                                 Description                                                                                 |
| ------------------------------------------------------------------------------------ | ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [character.html](character/character.html)                                           |              | A full character response.                                                                                                                                                  |
| [characterNotFound.html](character/characterNotFound.html)                           |              | A character not found page.                                                                                                                                                 |
| [characterRecentlyTraded.html](character/characterRecentlyTraded.html)               |              | A character that was traded and is also visible.                                                                                                                            |
| [characterScheduledForDeletion.html](character/characterScheduledForDeletion.html)   |              | A character scheduled for deletion.                                                                                                                                         |
| [characterWithComplexDeaths.html](character/characterWithComplexDeaths.html)         |              | A character with many types of deaths, such as deaths by summons, players, assisted deaths, etcetera.                                                                       |
| [characterWithComplexDeaths2021.html](character/characterWithComplexDeaths2021.html) |              | A character with August/September 2021 deaths, including traded player and summon cases. Retained alongside the newer November 2025 death list for those distinct examples. |
| [characterWithFormerNames.html](character/characterWithFormerNames.html)             |              | A character with former names.                                                                                                                                              |
| [characterWithFormerWorld.html](character/characterWithFormerWorld.html)             |              | A character with a former world.                                                                                                                                            |
| [characterWithMultipleHouses.html](character/characterWithMultipleHouses.html)       |              | A character with two houses.                                                                                                                                                |
| [characterWithNoBadgesSelected.html](character/characterWithNoBadgesSelected.html)   |              | A character with no selected badges.                                                                                                                                        |
| [characterWithSpecialPosition.html](character/characterWithSpecialPosition.html)     |              | A character with a special position.                                                                                                                                        |
| [characterWithTitleAndBadges.html](character/characterWithTitleAndBadges.html)       |              | A character with unlocked titles and badges.                                                                                                                                |
| [characterWithTruncatedDeaths.html](character/characterWithTruncatedDeaths.html)     |              | A character with too many deaths to be displayed.                                                                                                                           |

## Character bazaar

|                                              File                                              | Extracted On |                             Description                             |
| ---------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------- |
| [bazaarCurrentAuctions.html](characterBazaar/bazaarCurrentAuctions.html)                       |              | The content of the current auctions page.                           |
| [bazaarCurrentAuctionsWithFilters.html](characterBazaar/bazaarCurrentAuctionsWithFilters.html) |              | The content of the current auctions page with all filters selected. |
| [bazaarHistory.html](characterBazaar/bazaarHistory.html)                                       |              | The content of the auction history page.                            |
| [bazaarHistoryEmpty.html](characterBazaar/bazaarHistoryEmpty.html)                             |              | The content of the auction history page with no entries.            |

## CM post archive

|                                   File                                   | Extracted On |                        Description                         |
| ------------------------------------------------------------------------ | ------------ | ---------------------------------------------------------- |
| [cmPostArchiveInitial.html](cmPostArchive/cmPostArchiveInitial.html)     |              | The CM Post Archive's initial page, with no data selected. |
| [cmPostArchiveNoPages.html](cmPostArchive/cmPostArchiveNoPages.html)     |              | The CM Post Archive with a few results in a single page.   |
| [cmPostArchiveNoResults.html](cmPostArchive/cmPostArchiveNoResults.html) |              | The CM Post Archive with no results.                       |
| [cmPostArchivePages.html](cmPostArchive/cmPostArchivePages.html)         |              | The CM Post Archive with multiple pages.                   |

## Creatures

|                                      File                                       | Extracted On |              Description               |
| ------------------------------------------------------------------------------- | ------------ | -------------------------------------- |
| [creatureConvinceable.html](creature/creatureConvinceable.html)                 |              | A creature that can be convinced.      |
| [creatureElementalResistances.html](creature/creatureElementalResistances.html) |              | A creature with elemental descriptions |

## Creatures section

|                          File                           | Extracted On |      Description       |
| ------------------------------------------------------- | ------------ | ---------------------- |
| [creatureList.html](creaturesSection/creatureList.html) |              | The list of creatures. |

## Event schedule

|                                       File                                       | Extracted On |                                                                     Description                                                                     |
| -------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| [eventSchedule.html](eventSchedule/eventSchedule.html)                           |              | The event schedule.                                                                                                                                 |
| [eventScheduleSeptember2020.html](eventSchedule/eventScheduleSeptember2020.html) |              | The September 2020 event calendar as a page extract. Retained to test the earlier calendar and extract format alongside the October 2025 full page. |

## Fansites

|                  File                   | Extracted On |      Description      |
| --------------------------------------- | ------------ | --------------------- |
| [fansites.html](fansites/fansites.html) |              | The fansites section. |

## Forum announcements

|                                        File                                        | Extracted On |                      Description                      |
| ---------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------- |
| [forumAnnouncement.html](forumAnnouncement/forumAnnouncement.html)                 |              | An announcement post on Tibia.com.                    |
| [forumAnnouncementNotFound.html](forumAnnouncement/forumAnnouncementNotFound.html) |              | The page for an announcement post that doesn't exist. |

## Forum boards

|                                                        File                                                         | Extracted On |                           Description                           |
| ------------------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------- |
| [forumBoard.html](forumBoard/forumBoard.html)                                                                       |              | A forum board.                                                  |
| [forumBoardEmpty.html](forumBoard/forumBoardEmpty.html)                                                             |              | An empty forum board.                                           |
| [forumBoardInvalidPage.html](forumBoard/forumBoardInvalidPage.html)                                                 |              | A forum board on a page out of range.                           |
| [forumBoardNotFound.html](forumBoard/forumBoardNotFound.html)                                                       |              | The page shown for a board that doesn't exist.                  |
| [forumBoardWithAnnouncements.html](forumBoard/forumBoardWithAnnouncements.html)                                     |              | A forum board with announcements.                               |
| [forumBoardWithGoldenFrame.html](forumBoard/forumBoardWithGoldenFrame.html)                                         |              | A forum board with golden frames on some posts.                 |
| [forumBoardWithThreadByDeletedChar.html](forumBoard/forumBoardWithThreadByDeletedChar.html)                         |              | A forum board with a thread started by a deleted char.          |
| [forumBoardWithThreadByTradedChar.html](forumBoard/forumBoardWithThreadByTradedChar.html)                           |              | A forum board with a thread started by a traded char.           |
| [forumBoardWithThreadWithLastPostByDeletedChar.html](forumBoard/forumBoardWithThreadWithLastPostByDeletedChar.html) |              | A forum board with a thread with a last post by a deleted char. |
| [forumBoardWithThreadWithLastPostByTradedChar.html](forumBoard/forumBoardWithThreadWithLastPostByTradedChar.html)   |              | A forum board with a thread with a last post by a traded char.  |

## Forum sections

|                                      File                                       | Extracted On |             Description              |
| ------------------------------------------------------------------------------- | ------------ | ------------------------------------ |
| [forumSection.html](forumSection/forumSection.html)                             |              | A forum section.                     |
| [forumSectionEmpty.html](forumSection/forumSectionEmpty.html)                   |              | An empty forum section.              |
| [forumSectionWithEmptyBoard.html](forumSection/forumSectionWithEmptyBoard.html) |              | A forum section with an empty board. |

## Forum threads

|                                              File                                              | Extracted On |                           Description                           |
| ---------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------- |
| [forumThread.html](forumThread/forumThread.html)                                               |              | A forum thread.                                                 |
| [forumThreadInvalidPage.html](forumThread/forumThreadInvalidPage.html)                         |              | A forum thread on a page out of range.                          |
| [forumThreadNotFound.html](forumThread/forumThreadNotFound.html)                               |              | The page for forum thread that doesn't exist.                   |
| [forumThreadWithEditedPost.html](forumThread/forumThreadWithEditedPost.html)                   |              | A forum thread containing an edited post.                       |
| [forumThreadWithGoldenFrame.html](forumThread/forumThreadWithGoldenFrame.html)                 |              | A forum thread with a golden frame around it.                   |
| [forumThreadWithPostByDeletedChar.html](forumThread/forumThreadWithPostByDeletedChar.html)     |              | A forum thread containing a post by a deleted character.        |
| [forumThreadWithPostByTradedChar.html](forumThread/forumThreadWithPostByTradedChar.html)       |              | A forum thread containing a post by a traded character.         |
| [forumThreadWithPostWithGoldenFrame.html](forumThread/forumThreadWithPostWithGoldenFrame.html) |              | A forum thread containing a post with a golden frame around it. |

## Guilds

|                         File                         | Extracted On |                                Description                                |
| ---------------------------------------------------- | ------------ | ------------------------------------------------------------------------- |
| [guild.html](guild/guild.html)                       |              | The content of a guild's page.                                            |
| [guildAtWar.html](guild/guildAtWar.html)             |              | The content of a guild's page for a guild with an active war.             |
| [guildDisbanding.html](guild/guildDisbanding.html)   |              | A guild that is set to be disbanded.                                      |
| [guildFormation.html](guild/guildFormation.html)     |              | A guild still in formation.                                               |
| [guildMinimumInfo.html](guild/guildMinimumInfo.html) |              | A guild with the bare minimum (no description, no guildhall, no homepage) |
| [guildNotFound.html](guild/guildNotFound.html)       |              | The page shown for a guild that doesn't exist.                            |

## Guild wars

|                                     File                                     | Extracted On |                            Description                            |
| ---------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------- |
| [guildWarActiveAndHistory.html](guildWars/guildWarActiveAndHistory.html)     |              | A guild with an active war and two previous wars.                 |
| [guildWarEmpty.html](guildWars/guildWarEmpty.html)                           |              | A guild with no active wars and no war history.                   |
| [guildWarUnactiveAndHistory.html](guildWars/guildWarUnactiveAndHistory.html) |              | A guild with no active wars and a previous war (enemy disbanded). |

## Guilds section

|                                  File                                  | Extracted On |                  Description                  |
| ---------------------------------------------------------------------- | ------------ | --------------------------------------------- |
| [guildsSection.html](guildsSection/guildsSection.html)                 |              | The guild list of a world.                    |
| [guildsSectionNotFound.html](guildsSection/guildsSectionNotFound.html) |              | The guild list of a world that doesn't exist. |

## Highscores

|                                        File                                         | Extracted On |                            Description                             |
| ----------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------ |
| [highscores.html](highscores/highscores.html)                                       |              | The content of a correct highscore's page.                         |
| [highscoresBattleEyePvpFilters.html](highscores/highscoresBattleEyePvpFilters.html) |              | The content of the highscores page using BattlEye and PvP filters. |
| [highscoresExperience.html](highscores/highscoresExperience.html)                   |              | The content of an experience highscores page.                      |
| [highscoresGlobal.html](highscores/highscoresGlobal.html)                           |              | The content of the highscores for all worlds.                      |
| [highscoresLoyalty.html](highscores/highscoresLoyalty.html)                         |              | The content of a loyalty highscores page.                          |
| [highscoresNoResults.html](highscores/highscoresNoResults.html)                     |              | The content of the highscores page with no results.                |
| [highscoresNotFound.html](highscores/highscoresNotFound.html)                       |              | The content of the highscores page of a nonexistent world.         |

## Houses

|                                    File                                    | Extracted On |                              Description                               |
| -------------------------------------------------------------------------- | ------------ | ---------------------------------------------------------------------- |
| [houseAuctionedWithBids.html](house/houseAuctionedWithBids.html)           |              | A house on auction with bids.                                          |
| [houseAuctionedWithoutBids.html](house/houseAuctionedWithoutBids.html)     |              | A house on auction without any bids.                                   |
| [houseBeforeMerge.html](house/houseBeforeMerge.html)                       |              | A house from a world scheduled to be merged.                           |
| [houseNotFound.html](house/houseNotFound.html)                             |              | The content of a page for a house not found.                           |
| [houseRented.html](house/houseRented.html)                                 |              | The content of a house's page                                          |
| [houseRentedAcceptedTransfer.html](house/houseRentedAcceptedTransfer.html) |              | A rented house that will be transferred and has already been accepted. |

## Houses section

|                                             File                                             | Extracted On |                          Description                          |
| -------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------- |
| [housesSection.html](housesSection/housesSection.html)                                       |              | The house list of a world.                                    |
| [housesSectionBeforeMerge.html](housesSection/housesSectionBeforeMerge.html)                 |              | The houses section of a world that is scheduled to be merged. |
| [housesSectionEmpty.html](housesSection/housesSectionEmpty.html)                             |              | The house list of a world, showing no houses.                 |
| [housesSectionNotFound.html](housesSection/housesSectionNotFound.html)                       |              | The house list of a world or town that doesn't exist.         |
| [housesSectionWithAuctionedHouses.html](housesSection/housesSectionWithAuctionedHouses.html) |              | The house list containing houses on auction.                  |

## Kill statistics

|                                      File                                       | Extracted On |                                      Description                                      |
| ------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------- |
| [killStatisticsEmpty.html](killStatistics/killStatisticsEmpty.html)             |              | The content for the kill statistics page with no results.                             |
| [killStatisticsNotFound.html](killStatistics/killStatisticsNotFound.html)       |              | The content of the kill statistics page of a nonexistent world or a unselected world. |
| [killStatisticsWithResults.html](killStatistics/killStatisticsWithResults.html) |              | The content of a correct kill statistics' page.                                       |

## Leaderboard

|                                       File                                       | Extracted On |                        Description                        |
| -------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------- |
| [leaderboardCurrentRotation.html](leaderboard/leaderboardCurrentRotation.html)   |              | The leaderboard page for the current rotation of a world. |
| [leaderboardDeletedCharacter.html](leaderboard/leaderboardDeletedCharacter.html) |              | A leaderboard containing a deleted character.             |
| [leaderboardEmpty.html](leaderboard/leaderboardEmpty.html)                       |              | The leaderboard page for a world with no entries.         |
| [leaderboardNotFound.html](leaderboard/leaderboardNotFound.html)                 |              | The leaderboard page for a world that doesn't exist.      |

## News

|                                    File                                     | Extracted On |                         Description                         |
| --------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------- |
| [newsFeaturedArticle.html](news/newsFeaturedArticle.html)                   |              | The content of a featured article.                          |
| [newsNotFound.html](news/newsNotFound.html)                                 |              | The content of the page shown for an id that doesn't exist. |
| [newsPostWithDiscussionThread.html](news/newsPostWithDiscussionThread.html) |              | The content of a news post with a discussion thread.        |
| [newsTicker.html](news/newsTicker.html)                                     |              | The content of a news ticker.                               |

## News archive

|                                  File                                  | Extracted On |                              Description                              |
| ---------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------- |
| [newsArchiveEmpty.html](newsArchive/newsArchiveEmpty.html)             |              | The content of the news search page with no results.                  |
| [newsArchiveError.html](newsArchive/newsArchiveError.html)             |              | The content of the news search page with an error.                    |
| [newsArchiveInitial.html](newsArchive/newsArchiveInitial.html)         |              | The content of the news search page with results and default filters. |
| [newsArchiveWithFilters.html](newsArchive/newsArchiveWithFilters.html) |              | The content of the news search page with results using filters.       |

## Spells

|                                  File                                   | Extracted On |                  Description                  |
| ----------------------------------------------------------------------- | ------------ | --------------------------------------------- |
| [spell.html](spells/spell.html)                                         |              | A regular spell.                              |
| [spellMultilineDescription.html](spells/spellMultilineDescription.html) |              | A spell with a description of multiple lines. |
| [spellRevelationPerk.html](spells/spellRevelationPerk.html)             |              | A spell obtained from a revelation perk.      |
| [spellVariableMana.html](spells/spellVariableMana.html)                 |              | A spell with variable mana usage.             |
| [spellWithRune.html](spells/spellWithRune.html)                         |              | A spell that produces a rune.                 |
| [spellWithSecondaryGroup.html](spells/spellWithSecondaryGroup.html)     |              | A spell that has a secondary cooldown group.  |

## Spells section

|                                 File                                 | Extracted On |                            Description                             |
| -------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------ |
| [spellsSectionDefault.html](spellsSection/spellsSectionDefault.html) |              | The spells section with all results (no filters used).             |
| [spellsSectionEmpty.html](spellsSection/spellsSectionEmpty.html)     |              | The spells section with empty results (due to filter combination). |

## Worlds

|                            File                            | Extracted On |                                               Description                                               |
| ---------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------- |
| [worldExperimental.html](world/worldExperimental.html)     |              | An experimental world.                                                                                  |
| [worldGreenBattlEye.html](world/worldGreenBattlEye.html)   |              | A world that was initially protected by BattlEye.                                                       |
| [worldNeverOnline.html](world/worldNeverOnline.html)       |              | A world that has never been online.                                                                     |
| [worldNoTitles.html](world/worldNoTitles.html)             |              | A world without titles.                                                                                 |
| [worldNotFound.html](world/worldNotFound.html)             |              | The page shown for a world that doesn't exist.                                                          |
| [worldOffline.html](world/worldOffline.html)               |              | An offline world; covered by the source world parser tests (not listed in the source resource READMEs). |
| [worldOnline.html](world/worldOnline.html)                 |              | An online world on Tibia.com.                                                                           |
| [worldUnprotected.html](world/worldUnprotected.html)       |              | A world with no BattlEye protection.                                                                    |
| [worldYellowBattlEye.html](world/worldYellowBattlEye.html) |              | A world that was not initially protected by BattlEye.                                                   |

## World overview

|                                 File                                 | Extracted On |               Description               |
| -------------------------------------------------------------------- | ------------ | --------------------------------------- |
| [worldOverviewOffline.html](worldOverview/worldOverviewOffline.html) |              | The world list with all worlds offline. |
| [worldOverviewOnline.html](worldOverview/worldOverviewOnline.html)   |              | The world list with all worlds online.  |
