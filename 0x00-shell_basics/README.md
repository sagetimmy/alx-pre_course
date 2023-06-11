(defun print-current-directory ()
  "Prints the absolute path name of the current working directory."
  (interactive)
  (let ((current-directory (expand-file-name default-directory)))
    (message "Absolute path of the current working directory: %s" current-directory)))

(print-current-directory)

