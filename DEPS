# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '3b495e1450b19dd79c4493ec2fe9698d003e209f',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '19d232bb93a8585236051094cf49f747cc892e26',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '54a521dd130ae1b2f38fef79b09515702d135bdd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ba828b232c88c572624476c03c284a09c1b34f55',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'cacef3039d277c448c89336290ec3937270b0996',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1bc9d032a89ef9b09e5b395d2f93fcd59fedf8ad',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7efad3a101ea6e641e5948a4ed0d6e93b99b7bff',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '50563f48368d75281bc2fb1c3407dc531ce28910',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0bc2d8ef4d36047cf11b7615dffcc83f25464ec2',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
