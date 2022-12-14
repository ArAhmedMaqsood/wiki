---

database-plugin: basic

---

%% dbfolder:yaml
name: new database
description: new description
columns:
  __file__:
    key: "__file__"
    input: "markdown"
    label: "File"
    accessorKey: "__file__"
    isMetadata: "true"
    skipPersist: "false"
    isDragDisabled: "false"
    csvCandidate: "true"
    accessorkey: "__file__"
    position: "1"
    isHidden: "false"
    sortIndex: "-1"
    config:
      enable_media_view: "true"
      link_alias_enabled: "true"
      media_width: "100"
      media_height: "100"
      isInline: "false"
      task_hide_completed: "true"
  text_column:
    input: "text"
    accessorkey: "text_column"
    key: "text_column"
    label: "text column"
    position: "2"
    accessorKey: "text_column"
    skipPersist: "false"
    isHidden: "false"
    sortIndex: "-1"
    config:
      isInline: "false"
      media_height: "100"
      media_width: "100"
      enable_media_view: "false"
  selected_column:
    input: "select"
    accessorkey: "selected_column"
    key: "selected_column"
    label: "selected column"
    position: "3"
    accessorKey: "selected_column"
    skipPersist: "false"
    isHidden: "false"
    sortIndex: "-1"
    options:
    config:
      isInline: "false"
      media_height: "100"
      media_width: "100"
      enable_media_view: "false"
  number_column:
    input: "number"
    accessorkey: "number_column"
    key: "number_column"
    label: "number column"
    position: "4"
    accessorKey: "number_column"
    skipPersist: "false"
    isHidden: "false"
    sortIndex: "-1"
    config:
      isInline: "false"
      media_height: "100"
      media_width: "100"
      enable_media_view: "false"
  Datetime_column:
    input: "calendar_time"
    accessorkey: "Datetime_column"
    key: "Datetime_column"
    label: "Datetime column"
    position: "6"
    accessorKey: "Datetime_column"
    skipPersist: "false"
    isHidden: "false"
    sortIndex: "-1"
    config:
      enable_media_view: "true"
      media_width: "100"
      media_height: "100"
      isInline: "false"
      source_data: "current_folder"
  Date_column:
    input: "calendar"
    accessorkey: "Date_column"
    key: "Date_column"
    label: "Date column"
    position: "5"
    accessorKey: "Date_column"
    skipPersist: "false"
    isHidden: "false"
    sortIndex: "-1"
    config:
      enable_media_view: "true"
      media_width: "100"
      media_height: "100"
      isInline: "false"
      source_data: "current_folder"
  __created__:
    key: "__created__"
    input: "calendar_time"
    label: "Created"
    accessorKey: "__created__"
    isMetadata: "true"
    isDragDisabled: "false"
    skipPersist: "false"
    csvCandidate: "true"
    accessorkey: "__created__"
    position: "8"
    isHidden: "false"
    sortIndex: "-1"
    config:
      enable_media_view: "true"
      link_alias_enabled: "true"
      media_width: "100"
      media_height: "100"
      isInline: "false"
      task_hide_completed: "true"
  __modified__:
    key: "__modified__"
    input: "calendar_time"
    label: "Modified"
    accessorKey: "__modified__"
    isMetadata: "true"
    isDragDisabled: "false"
    skipPersist: "false"
    csvCandidate: "true"
    accessorkey: "__modified__"
    position: "9"
    isHidden: "false"
    sortIndex: "-1"
    config:
      enable_media_view: "true"
      link_alias_enabled: "true"
      media_width: "100"
      media_height: "100"
      isInline: "false"
      task_hide_completed: "true"
  checkbox_column:
    input: "checkbox"
    accessorkey: "checkbox_column"
    key: "checkbox_column"
    label: "checkbox column"
    position: "7"
    accessorKey: "checkbox_column"
    skipPersist: "false"
    isHidden: "false"
    sortIndex: "-1"
    config:
      enable_media_view: "true"
      media_width: "100"
      media_height: "100"
      isInline: "false"
      source_data: "current_folder"
  tags_column:
    input: "tags"
    accessorkey: "tags_column"
    key: "tags_column"
    label: "tags column"
    position: "4"
    accessorKey: "tags_column"
    skipPersist: "false"
    isHidden: "false"
    sortIndex: "-1"
    options:
      - { label: "new tag", backgroundColor: "hsl(247, 95%, 90%)"}
    config:
      enable_media_view: "true"
      media_width: "100"
      media_height: "100"
      isInline: "false"
      source_data: "current_folder"
  __tasks__:
    key: "__tasks__"
    input: "task"
    label: "Task"
    accessorKey: "__tasks__"
    isMetadata: "true"
    isDragDisabled: "false"
    skipPersist: "false"
    csvCandidate: "false"
    isHidden: "false"
    sortIndex: "-1"
    config:
      enable_media_view: "true"
      link_alias_enabled: "true"
      media_width: "100"
      media_height: "100"
      isInline: "false"
      task_hide_completed: "true"
config:
  enable_show_state: "false"
  group_folder_column: 
  remove_field_when_delete_column: "true"
  cell_size: "normal"
  sticky_first_column: "false"
  show_metadata_created: "true"
  show_metadata_modified: "true"
  source_data: "current_folder"
  source_form_result: "\"root\""
  show_metadata_tasks: "true"
  remove_empty_folders: "false"
  automatically_group_files: "false"
  hoist_files_with_empty_attributes: "true"
  show_metadata_inlinks: "false"
  show_metadata_outlinks: "false"
  source_destination_path: "/"
  frontmatter_quote_wrap: "true"
  row_templates_folder: "/"
  current_row_template: 
  pagination_size: "10"
  enable_js_formulas: "false"
  formula_folder_path: "/"
  inline_default: "false"
  inline_new_position: "top"
  date_format: "yyyy-MM-dd"
  datetime_format: "yyyy-MM-dd HH:mm:ss"
filters:
  enabled: false
  conditions:
%%